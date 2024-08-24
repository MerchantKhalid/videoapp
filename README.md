Zoom Clone
This project is built with Next.js and TypeScript, replicating the core features of Zoom, including secure login, meeting creation, and a variety of meeting controls like recording, screen sharing, and participant management.

⚙️ Tech Stack
Next.js
TypeScript
Clerk
getstream
shadcn
Tailwind CSS
🔋 Features
Authentication: Secure login with Clerk, supporting social sign-on and email/password.
New Meeting: Start meetings with configurable camera and microphone settings.
Meeting Controls: Manage recordings, screen sharing, muting, layout, and participants.
Exit Meeting: Leave or end meetings for all participants.
Schedule Meetings: Plan future meetings with easy access via 'Upcoming Meetings.'
Past Meetings: View details and recordings of previous meetings.
Personal Room: Instant meetings via a unique, shareable link.
Join via Link: Easily join meetings with a provided link.
Secure Real-time Functionality: Ensures privacy and data integrity.
Responsive Design: Optimized for all devices and screen sizes.
🤸 Quick Start
Prerequisites
Ensure you have:

Git
Node.js
npm
Setup
Clone the Repository:

bash
Copy code
git clone https://github.com/MerchantKhalid/videoapp.git
cd zoom-clone
Install Dependencies:

bash
Copy code
npm install
Set Up Environment Variables: Create a .env file in the project root:

plaintext
Copy code
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
Replace placeholders with your Clerk and getstream credentials.

Run the Project:

bash
Copy code
npm run dev
Open http://localhost:3000 in your browser.
