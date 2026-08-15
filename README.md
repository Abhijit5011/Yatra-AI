
## Yatra AI — Your Smart Travel Partner

<div align="left">
  <a href="https://yatra-ai-tourism.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-00C853?style=for-the-badge&logo=vercel&logoColor=white">
  </a>
  <a href="https://github.com/Abhijit5011/Yatra-AI">
    <img src="https://img.shields.io/badge/GitHub%20Repo-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="https://youtu.be/uB0CDXoR1d0">
    <img src="https://img.shields.io/badge/Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
  </a>
</div>

<p>
<strong>
An AI-first tourism intelligence platform that transforms travel preferences, constraints, and location data into personalized recommendations, dynamic itineraries, and actionable travel insights.
</strong>
</p>

<h3>Key Features & Impact</h3>

<ul>
<li><strong>AI Recommendation Engine:</strong> Gemini-powered contextual destination intelligence.</li>

<li><strong>Generative Itinerary Engine:</strong> Dynamic day-wise travel planning with LLM-driven recommendations.</li>

<li><strong>Review & Geospatial Intelligence:</strong> Review synthesis with location-aware interactive mapping.</li>

<li><strong>Secure Application Architecture:</strong> Supabase PostgreSQL, RLS, role-based access, and responsive Tailwind UI.</li>

  <li>
    <strong>Tech Stack:</strong>
    <code style="background-color:#4DB6D6;color:#fff;padding:4px 8px;border-radius:5px;">React</code>
    <code style="background-color:#646CFF;color:#fff;padding:4px 8px;border-radius:5px;">Vite</code>
    <code style="background-color:#5961C9;color:#fff;padding:4px 8px;border-radius:5px;">TypeScript</code>
    <code style="background-color:#1595A8;color:#fff;padding:4px 8px;border-radius:5px;">Tailwind CSS</code>
    <code style="background-color:#329B6E;color:#fff;padding:4px 8px;border-radius:5px;">Supabase Postgres</code>
    <code style="background-color:#735F91;color:#fff;padding:4px 8px;border-radius:5px;">Gemini API</code>

  </li>
</ul>


<table>
<tr>
<td width="50%">
<img src="https://raw.githubusercontent.com/Abhijit5011/abhijit5011/main/Yatra%20AI/Screenshot%202026-01-09%20001756.png" width="100%" alt="Yatra AI Dashboard">
</td>
<td width="50%">
<img src="https://raw.githubusercontent.com/Abhijit5011/abhijit5011/main/Yatra%20AI/Screenshot%202026-01-09%20001906.png" width="100%" alt="Yatra AI Recommendations">
</td>
</tr>

<tr>
<td width="50%">
<img src="https://raw.githubusercontent.com/Abhijit5011/abhijit5011/main/Yatra%20AI/Screenshot%202026-01-09%20002205.png" width="100%" alt="Yatra AI Itinerary">
</td>
<td width="50%">
<img src="https://raw.githubusercontent.com/Abhijit5011/abhijit5011/main/Yatra%20AI/Screenshot%202026-01-09%20002224.png" width="100%" alt="Yatra AI Travel Intelligence">
</td>
</tr>
</table>

## Setup Instructions

1. **Environment Variables**:
   Set the following Gemini API Key in edge function of Supabase:
   - `GEMINI_API_KEY`: Your Google Gemini API Key.
2. **Set the following Supabase variables**:
   - `SUPABASE_URL`: Your Supabase Project URL.
   - `SUPABASE_ANON_KEY`: Your Supabase Anon Key.

2. **Database Schema**:
   Run the SQL provided in `services/supabase.ts` inside your Supabase SQL editor to create the necessary tables and relationships.

3. **Install Dependencies**:
   ```bash
   npm install @google/genai @supabase/supabase-js react-router-dom lucide-react
   ```

4. **Run Application**:
   ```bash
   npm run start
   ```

