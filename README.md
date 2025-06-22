html {
  box-sizing: border-box;
}
*, *::before, *::after {
  box-sizing: inherit;
}

/* Basic Body Styles for better font and margin control */
body {
  font-family: sans-serif; /* Example: You can change this to your preferred font */
  margin: 0; /* Remove default body margin */
  line-height: 1.6; /* Improve readability of text */
  background-color: #f4f7fa; /* A light background for the whole page */
}

/* --- Header Styling --- */
header {
  background-color: #0b3d91;
  color: white;
  text-align: center;
  padding: 30px 15px;
}

header h1 {
  margin: 0;
  font-size: 32px;
}

header p {
  margin-top: 8px;
  font-size: 16px;
}

/* --- Main Content Area Styling --- */
main {
  max-width: 700px;
  margin: 40px auto;
  background-color: #ffffff;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 0 12px rgba(0, 0, 0, 0.1);
}

/* --- Form Element Styling --- */
label {
  font-weight: bold;
  display: block;
  margin-top: 20px;
}

input, select, textarea {
  width: 100%;
  padding: 10px;
  margin-top: 8px;
  border: 1px solid #ccc;
  border-radius: 6px;
  font-size: 16px;
  /* Ensure consistent appearance */
  -webkit-appearance: none; /* Remove default styling on some browsers */
  -moz-appearance: none;
  appearance: none;
}

/* Style for focus state for accessibility */
input:focus, select:focus, textarea:focus {
  outline: none;
  border-color: #0b3d91; /* Highlight border on focus */
  box-shadow: 0 0 0 3px rgba(11, 61, 145, 0.2); /* Subtle glow on focus */
}

/* --- Button Styling --- */
button {
  margin-top: 25px;
  padding: 12px 20px;
  background-color: #0b3d91;
  color: white;
  font-size: 16px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s ease; /* Smooth transition for hover effect */
}

button:hover {
  background-color: #072b6b;
}

/* --- Footer Styling --- */
footer {
  text-align: center;
  background-color: #0b3d91;
  color: white;
  padding: 15px;
  margin-top: 40px;
}

/* --- Responsive Adjustments --- */
@media (max-width: 768px) {
  main {
    margin: 20px; /* Adjust margin for smaller screens */
    padding: 20px; /* Adjust padding for smaller screens */
  }

  header {
    padding: 20px 10px; /* Slightly reduce header padding on smaller screens */
  }
}

/* Further adjustments for very small screens (e.g., phones) */
@media (max-width: 480px) {
    header h1 {
        font-size: 28px;
    }

    header p {
        font-size: 14px;
    }

    main {
        margin: 15px;
        padding: 15px;
    }

    input, select, textarea, button {
        font-size: 15px;
    }

    button {
        padding: 10px 15px;
    }
}
