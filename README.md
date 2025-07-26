# KBz - Antimicrobial Susceptibility Analyzer

An interactive web-based tool for determining antimicrobial susceptibility based on the Kirby-Bauer disk diffusion method. This application provides a user-friendly interface to classify microorganisms as Susceptible, Intermediate, or Resistant based on their zone of inhibition diameter.

**Project made by Naman Devadiga. Happy Learning!!**

[![Screenshot-2025-07-26-172120.png](https://i.postimg.cc/KvLbW0hT/Screenshot-2025-07-26-172120.png)](https://postimg.cc/Wh2xF63p)

---

## About The Project

The KBz Susceptibility Analyzer is a single-page application designed for microbiology students, technicians, and researchers. It simplifies the process of interpreting antibiotic susceptibility test results by providing instant classification based on embedded reference data from the HiMedia chart. The tool features a dynamic user interface with a real-time visual representation of a petri dish, making the interpretation process more intuitive and educational.

This project is built with vanilla HTML, CSS, and JavaScript, and it uses Tailwind CSS for styling. All the necessary data is self-contained within the HTML file, making it a portable, serverless application that can be run directly in any modern web browser.

## Key Features

* **Interactive Susceptibility Classification:** Instantly classifies a microorganism as Susceptible, Intermediate, or Resistant when you input the zone of inhibition diameter.
* **Visual Petri Dish Representation:** A dynamic SVG petri dish that visually represents the zone of inhibition, with colors changing based on the classification result.
* **Searchable Antimicrobial Agent Dropdown:** A user-friendly, searchable dropdown menu to quickly find and select from a long list of antimicrobial agents.
* **Dynamic Filtering:** The dropdowns for Microorganism and Disc Content are dynamically populated based on the selected antimicrobial agent, preventing invalid combinations.
* **Embedded HiMedia Reference Data:** The application uses a comprehensive, built-in dataset based on the HiMedia Susceptibility Test Reference Chart.
* **Responsive Design:** The interface is fully responsive and works seamlessly on desktops, tablets, and mobile devices.
* **Self-Contained & Portable:** The entire application is contained within a single HTML file and requires no backend or special setup to run.

## Technologies Used

* **HTML5:** For the structure and content of the application.
* **Tailwind CSS:** For all styling and creating a modern, responsive user interface.
* **JavaScript (ES6+):** For all the application logic, including data parsing, dynamic UI updates, and result calculations.
* **Font Awesome:** For the icons used in the input fields.

## Getting Started

To run this project locally, simply download the `index.html` file and open it in your web browser.

1.  **Clone the repository or download the source code:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repository-name
    ```
3.  **Open the `index.html` file in your browser.**
    You can do this by double-clicking the file or by right-clicking and selecting "Open with" your preferred browser.

## Data Source

The interpretive criteria for this application are based on the **HiMedia Susceptibility Test Reference Chart**. The data has been extracted and embedded directly into the application's source code. You can download the original reference document from the following link:

[HiMedia Susceptibility Test Reference Chart](https://www.himedialabs.com/media/Catalogue/literature/microbiology/antimicrobial-susceptibility-systems.pdf)

## License

This project is distributed under the MIT License. See the `LICENSE` file for more information.
