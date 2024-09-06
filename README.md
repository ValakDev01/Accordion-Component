# Accordion Component Project 💥

<br />

## Description 💬

This project is a React-based accordion component for displaying frequently asked questions (FAQs). The main App component renders the Accordion component, which receives an array of FAQ objects containing titles and texts.

The Accordion component maps over the FAQ data, creating an AccordionItem for each entry. Each AccordionItem manages its own open/closed state using the useState hook. When an item is clicked, it toggles its open state, showing or hiding the answer text.

The AccordionItem component displays the item's title and an icon indicating whether the section is open or closed. It also shows a number prefix for each FAQ item. When an item is open, the answer text is revealed, providing a user-friendly way to explore the FAQs.

<img width="1508" alt="Screenshot 2024-09-06 at 13 58 12" src="https://github.com/user-attachments/assets/62224e9a-bf2b-43de-b19e-790deeb482d3">
