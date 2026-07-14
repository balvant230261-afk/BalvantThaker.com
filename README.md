Balvant Thaker — Personal Professional Website

A single-page personal website for Balvant Thaker, an Accounts & Administrative Professional based in Port Coquitlam, BC, Canada.

Live site: [add your Netlify/GitHub Pages URL here once deployed]

About This Project

This is a self-contained, single-file website — everything (HTML structure, CSS styling, and JavaScript functionality) lives inside index.html. There's no build process, no dependencies to install, and no server required. Open the file in any browser and it works.

Features


Hero, About, Skills, Experience, Education & Volunteer sections — a full professional profile
Photo gallery — "Visual Stories" showcasing community events and recognitions
Live appointment booking system

Interactive weekly date picker (Monday–Friday only)
45-minute time slots, 9:00 AM–5:00 PM
Prevents double-booking by checking a connected Google Sheet in real time
Booked slots persist locally across browser sessions and automatically reset each new year
"Other" service option with a pop-up to specify details



Helen — AI Assistant widget

Answers visitor questions about Balvant's background, using only his resume data
Politely declines to answer anything outside that scope



Fully responsive — works on desktop, tablet, and mobile
News & Events, Contact, and downloadable resume sections


How the Booking System Works


A visitor picks a date and time and submits their details.
The request is sent to a Zapier webhook.
Zapier checks a Google Sheet (the booking log) to confirm the slot is still free.
If free: a Google Calendar event is created, and confirmation emails go out to both Balvant and the client.
If already taken: the visitor is notified so they can pick another time.


Setup details for the Zapier side are documented separately (see zapier-double-booking-check.md if included in this repo).

Tech Stack


Plain HTML5, CSS3, and vanilla JavaScript — no frameworks, no build tools
Google Sheets + Google Calendar (via Zapier) for appointment data
All images embedded directly in the HTML as base64 — no external image files needed


Deployment

This site can be hosted on any static hosting service, including:


Netlify
GitHub Pages
Cloudflare Pages


To deploy: upload/drag in index.html (make sure it's named exactly that for most hosts to recognize it as the homepage).

Local Preview

No installation needed — just open index.html directly in any web browser.

Contact


Phone: (778) 266-9654
Email: balvant_200@yahoo.com
Location: Port Coquitlam, BC, Canada  
