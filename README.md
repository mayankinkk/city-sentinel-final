🏙️ City Sentinel
City Sentinel is a civic-tech web application that empowers citizens to report local infrastructure issues and helps authorities track, manage, and resolve them efficiently.
It bridges the gap between citizens and local authorities through transparency, real-time updates, and role-based dashboards.

🚀 Problem Statement
Urban issues such as potholes, broken streetlights, drainage problems, and garbage overflow often go unreported or unresolved due to lack of a centralized, transparent system.

City Sentinel solves this by:

 •Allowing citizens to report issues with location and evidence

 •Enabling authorities to manage and resolve complaints efficiently

 •Providing transparency in issue status and resolution

✨ Key Features

👥 User Roles
City Sentinel supports multiple roles, each with specific permissions:

    •Citizen (User)

    •Moderator

    •Department Authority

    •Admin

    •Super Admin

🧑‍🤝‍🧑 Citizen Features
 •Report civic issues with title, description, category, and priority

 •Attach images as proof

 •Auto-detect or manually select location on map

 •Track issue status (Pending → In Progress → Resolved)

 •View all reported issues on an interactive map

 •Secure authentication (email / magic link / OAuth)

 •Profile management

🗺️ Live Map & Issue Visualization
 •Interactive map view of all reported issues

 •Marker-based visualization for easy identification

 •Click markers to view issue details

 •Helps identify high-risk or problem-prone areas

🛠️ Authority & Moderator Features
 •Role-based dashboards

 •View issues assigned to their department or region

 •Update issue status and resolution progress

 •Moderate or verify reported issues

 •Access analytics for better decision-making

📊 Dashboard & Analytics
 •Total reported issues

 •Issues by category (roads, lighting, drainage, etc.)

 •Pending vs resolved statistics

 •Department-wise and role-wise insights

 •Helps authorities prioritize work efficiently

🔔 Notifications
  •Real-time notifications for:

 •Status updates

 •New reports

 •Actions taken by authorities

 •Keeps users informed and engaged

🔐 Authentication & Security
 •Secure authentication using Supabase

 •Role-based access control

 •Protected routes for dashboards and admin panels

 •Email verification support

🎨 UI & UX
 •Clean, responsive design (mobile-friendly)

 •Dark / light theme toggle

 •Intuitive navigation

 •Accessible and modern interface

🧱 Tech Stack
Frontend
    •React + TypeScript

    •Vite

    •Tailwind CSS

    •Shadcn/UI

    •Lucide Icons

    •React Router

Backend / Services
    •Supabase (Auth, Database, Storage)

    •PostgreSQL

    •Row Level Security (RLS)

Maps & Visualization
    •Leaflet

    •React-Leaflet


📁 Project Structure

city-sentinel/
├── public/
│   └── favicon.ico
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── layout/
│   │   ├── dashboard/
│   │   ├── notifications/
│   ├── pages/
│   ├── hooks/
│   ├── lib/
│   ├── types/
│   ├── App.tsx
│   └── main.tsx
├── supabase/
├── index.html
├── package.json
└── README.md


⚙️ Installation & Setup
1️⃣ Clone the repository
bash
Copy code
git clone https://github.com/mayankinkk/city-sentinel.git
cd city-sentinel
2️⃣ Install dependencies
bash
Copy code
npm install --legacy-peer-deps
3️⃣ Run the development server
bash
Copy code
npm run dev
The app will run


🔮 Future Enhancements
 •AI-based duplicate issue detection

 •Heatmap view for issue density

 •Push notifications

 •SLA-based resolution tracking

 •Mobile app version

 •Integration with municipal systems

🤝 Contribution
Contributions are welcome!
Feel free to fork the repository, create a feature branch, and submit a pull request.

📜 License
This project is open-source and available under the MIT License.

👨‍💻 Author
Mayank Sharma
B.Tech CSE
Passionate about full-stack development, and building impactful products.