# EcoTrack-AI
Personal Carbon Footprint Awareness Platform

PromptWars (H2S) — Challenge 3 submission.

Live demo

Visit:

Chosen Vertical

EcoTrack AI is a Carbon Footprint Awareness Platform designed to help individuals understand, track, and reduce their carbon emissions. By analyzing daily lifestyle activities such as transportation, energy consumption, food habits, and waste generation, the platform provides meaningful insights that encourage sustainable living and environmentally responsible decision-making.

Approach and logic

1. Measure what matters. Carbon emissions are calculated across four categories — travel, home energy, diet, and waste — using standard emission factors.
2. Visualize the impact. Results are displayed through interactive charts and sustainability indicators, making emissions easy to understand and compare.
3. Insight, not information overload. The platform identifies the largest emission source and generates a personalized, data-driven recommendation with the highest potential impact.
4. Awareness through action. Users can recalculate and compare results over time to build more sustainable habits.
5. Privacy by design. All calculations run in the browser. No accounts, no personal data storage, and no server-side processing.

How It Works

. User enters data for travel, home energy, diet, and waste.
. calculateFootprint() converts activities into estimated kg CO₂e emissions.
. Emissions are grouped by category and summed into a total footprint.
. generateInsights() identifies the highest-impact category.
. Personalized recommendations are generated based on the user's own footprint data.
. Results are visualized instantly through interactive charts and dashboards.

Assumptions

. Emission factors are simplified global averages for educational awareness.
. User-provided data is assumed to be reasonably accurate.
. Results are estimates and not a certified carbon audit.
. Recommendations are based on common sustainability practices.
. Data is processed locally and is not stored permanently.

Tech

Plain HTML, CSS, and Vanilla JavaScript.
Responsive design for desktop and mobile devices.
Client-side calculations with no backend dependency.
Lightweight architecture with fast load times.
Hosted on Netlify and managed through GitHub.
