# 🇪🇸 Spanish Verb Practice Application 🇪🇸

Welcome to your interactive tool for mastering Spanish verbs! This single-page web application allows you to explore, practice, and understand verb conjugations in a dynamic and self-paced way.

## 🌟 Features

This application is designed to help you overcome the challenges of Spanish verb conjugation, offering the following functionalities:

* **Verb Tense Navigation:**
    * **Present Indicative** (`Presente de Indicativo`)
    * **Preterite** (`Pretérito Indefinido`)
    * **Imperfect** (`Pretérito Imperfecto`)
    * **Present Perfect** (`Pretérito Perfecto Compuesto`)
    * **Future Simple** (`Futuro Simple`)
    * **Conditional Simple** (`Condicional Simple`)
    * **Past Tenses Comparison** (to understand key differences)

* **Interaction Modes for Each Verb Tense:**
    * **View Conjugation:** Enter an infinitive verb, and the application will display its complete conjugation for that tense, along with its English translation.
    * **Practice Conjugation:** Enter a verb, and the application will present an empty table for you to fill in the conjugations.
        * **Check Answers:** Verify if your conjugations are correct, with visual feedback (✅ or ❌).
        * **Show Answers:** Reveal the correct conjugations in an additional column, allowing you to directly compare your answers.
        * **Suggest Random Verb:** Generate a random verb for practice, ideal for varying your study sessions.

* **Verb Identification Tool:**
    * **Find Infinitive:** Enter a conjugated verb form, and the application will attempt to find its infinitive.
    * **Identify Conjugation:** Enter a conjugated verb form, and the application will tell you the verb tense, person (I, you, he/she, etc.), and the infinitive it belongs to.

## 🚀 How to Use

1.  **Download the file:** Save the HTML code content into a file named `spanish_verbs_app.html` (make sure the extension is `.html`).
2.  **Open in your browser:** Double-click the `spanish_verbs_app.html` file. It will automatically open in your default web browser.
3.  **Explore the tabs:** Navigate between the different verb tenses and the identification section using the tabs at the top.
4.  **Practice modes:** Within each verb tense, switch between "View Conjugation" and "Practice Conjugation" modes to tailor your study.

## 🌐 Hosting

This is a single-page application (SPA) and can be easily hosted on static site hosting services like [GitHub Pages](https://pages.github.com/). Simply upload the `spanish_verbs_app.html` file to a public GitHub repository and configure GitHub Pages to serve it from the `main` (or `master`) branch.

## 🛠️ Technologies Used

* **HTML5:** Application structure.
* **Tailwind CSS:** Styling and responsive design.
* **JavaScript (Vanilla JS):** Interactive logic, data handling, and conjugation/identification functionalities.

## ✍️ Contribute and Expand

The verb and conjugation database is embedded directly within the JavaScript code. If you wish to add more verbs or improve the accuracy of the identifier and translations, you can edit the `spanish_verbs_app.html` file and modify the `verbData`, `verbTranslations`, and `infinitiveLookup` objects in the `<script>` section.

---

We hope this tool proves very useful in your Spanish learning journey! Happy practicing!
