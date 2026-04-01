Explori

Explori is a project I built to improve how people discover events in different cities. I wanted to create something that feels simple to use while still handling real data and interactions behind the scenes.

The main idea is straightforward. Users can explore events based on location, with a focus on clarity and ease of navigation rather than overwhelming them with information. I paid close attention to how the interface flows, not just how it looks.

Development Process

This project started small, but it became more complex as soon as I began adding real functionality. What began as a basic page quickly turned into a system that needed to manage data, state, and user interaction across multiple components.

I built the project using Next.js with the App Router, along with React and Tailwind CSS. While these tools made development faster, they also introduced challenges that forced me to understand how everything fits together.

Challenges

One of the biggest challenges was working with the App Router. At first, I did not fully understand the difference between server and client components. This led to issues where parts of the application would not behave as expected. I had to spend time learning where code runs and why certain features require a client component.

State management was another difficult area. Passing data through multiple layers of components quickly became hard to manage. I moved to using context, which improved structure, but introduced new problems with unnecessary re-renders. Fixing this required learning how to stabilize values and use memoization properly.

I also ran into several smaller issues that took longer than expected to debug. In many cases, the problem was not complex, but it required careful thinking to identify what was actually going wrong instead of guessing.

Results

By the end of the project, I had built something that is functional, organized, and easier to extend. More importantly, I developed a stronger understanding of how Next.js works, especially with server and client components.

Future Improvements

There are still areas I would improve if I continue working on Explori. These include refining the structure of the codebase, improving performance as more data is added, and expanding features such as filtering or personalization.

Run the project using "npm run dev"

Then open https://localhost:3000 in your own personal browser.
