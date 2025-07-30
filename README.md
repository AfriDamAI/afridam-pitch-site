AfriDam AI: An AI-Powered Dermatologist for Resource-Constrained Environments
Live Frontend Demo: https://afridamai.github.io/afridam-pitch-site/

Inspiration
The inspiration for AfriDam AI comes from my direct, lived experience as both a Nigerian Nurse and an AI Developer. In clinics, I witnessed the real-world consequences of a broken skincare system: patients suffering from the misuse of harmful products and a near-total lack of access to specialist dermatological care. As a developer, I saw the technical root of the problem: a global AI ecosystem with a massive data bias, trained almost exclusively on Caucasian skin, making it dangerously ineffective for Africans.

This isn't just a tech gap; it's a crisis of access, trust, and equity. I was inspired to build a solution from the ground up—by an African, for Africans—to create the trustworthy, intelligent tool that our communities deserve.

What it does
AfriDam AI is a functional prototype of an AI-powered dermatologist designed for resource-constrained environments. It has two core features:

AI Skin Scanner: A user can upload a photo of a skin concern. The app simulates an AI analysis and returns a potential diagnosis, a confidence score, and a brief description. This demonstrates the complete user journey for our core diagnostic feature.

Harmful Ingredient Checker: A user can paste a list of ingredients from a skincare product. Our backend checks this list against a database of known harmful agents (like mercury, hydroquinone, and steroids) and immediately flags any potential issues, providing a reason for each. This helps users make safer choices and combats the dangerous black market of unregulated products.

How we built it
The project is built on a simple, robust client-server model designed for accessibility and performance on low-end devices.

Frontend (index.html): A single, lightweight HTML file styled with Tailwind CSS to be fast and responsive. All user interactions, including file uploads and API calls, are handled with vanilla JavaScript to ensure maximum compatibility and minimal overhead.

Backend (app.py): A lightweight API built with Python and the Flask framework. It serves two main endpoints: /analyze to simulate the AI model's response for the skin scanner, and /check-ingredients to process and validate the ingredient list. The architecture is designed to offload all heavy computation to the server, keeping the client-side app small and data-efficient.

Challenges we ran into
The single greatest challenge is the "data desert"—the lack of a large-scale, ethically-sourced dataset of dermatological conditions on melanin-rich skin.

For this prototype, the challenge was to build a compelling user experience without the final AI model. The solution was to simulate the AI's response on the backend. This allowed us to build and test the complete user journey and prove that our system architecture is sound and ready for the real model once our clinical data partnerships are in place.

Accomplishments that we're proud of
A Fully Functional, End-to-End Prototype: We successfully built two core features, not just one, demonstrating a holistic approach to solving the skincare crisis.

A Professional and Trustworthy UI/UX: The design and user flow provide a clean, reassuring experience, which is critical for building user trust in a health-tech application.

Smart Architectural Decisions: By choosing a lightweight frontend and a cloud-based backend, we have built a prototype that is already optimized for the resource-constrained environments we aim to serve.

What we learned
UX is the Most Important Feature: For a health-tech app targeting a community with broken trust, the user experience is not just about aesthetics; it's about building confidence.

The Power of Prototyping: This prototype proved the viability of our technical approach and allows us to demonstrate the full vision of the product without waiting for months of data collection.

Constraints Inspire Creativity: Designing for low data, low connectivity, and low compute power is a design principle that leads to a more accessible and scalable product.

What's next for AfriDam AI
This prototype is the foundation for our 90-day execution sprint to build our investor-ready MVP. Our next steps are:

Secure Clinical Data Partnerships: Actively forge partnerships with dermatology clinics in Nigeria to begin ethically sourcing the proprietary data needed to train our real AI model.

Train the V1 Model: Use the data from our partners to train the first version of our proprietary Vision Language Model, replacing the simulation in the backend with a real, intelligent engine.

Launch a Closed Beta: Onboard the first users from our waitlist to gather real-world feedback, test the model's accuracy, and iterate on the product before a public launch.
