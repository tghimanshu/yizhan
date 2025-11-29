# Art Exhibition Website

## 1. Project Overview
This project is a static front-end website designed for an Art Exhibition platform. It allows users to browse latest exhibitions, view featured artists, read news articles, and learn about the organization. The website is built using HTML5 and CSS3, emphasizing a clean, visual-first design suitable for art content.

## 2. File Structure

```
├── about.html               # 'About Us' page
├── artist.html              # List of featured artists
├── css/                     # Directory containing all stylesheets
│   ├── about.css            # Styles for about.html
│   ├── artist.css           # Styles for artist.html
│   ├── base.css             # Global base styles (resets, common elements)
│   ├── exhibition_details.css # Styles for exhibition details page
│   ├── index.css            # Styles for the homepage
│   ├── latest_exhibition.css # Styles for exhibition listing page
│   ├── news.css             # Styles for news listing page
│   ├── news_details.css     # Styles for news article details
│   └── style.css            # Icon font definitions
├── exhibition_details.html  # Detailed view of a specific exhibition
├── fonts/                   # Directory for icon fonts (icomoon)
├── images/                  # Directory for website images (banners, logos, content)
├── index.html               # Homepage (entry point)
├── latest_exhibition.html   # List of all exhibitions
├── news.html                # News center listing
├── news_details.html        # Detailed view of a news article
└── test.html                # Sandbox file for layout testing
```

## 3. Installation & Setup
Since this is a static website, no complex installation or build process is required.

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    ```
2.  **Open the project:**
    Navigate to the project directory.
3.  **Run the website:**
    Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge).

## 4. Usage
-   **Navigation:** Use the top navigation bar to switch between Home, Latest Exhibitions, Artists, News Center, and About Us.
-   **Search:** A search bar is available in the header (currently static UI).
-   **Content:** Click on exhibition cards or news items to view detailed information.

## 5. Development
-   **HTML:** The structure is semantic where possible. Comments have been added to explain major sections.
-   **CSS:** Styles are modularized by page. `base.css` contains common styles. `style.css` handles icons.
-   **Images:** Ensure all new images are placed in the `images/` directory.

## 6. License
[Insert License Information Here]
