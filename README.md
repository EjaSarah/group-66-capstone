# Waste2Build — Resource Recovery Marketplace (Capstone)

Waste2Build is a role-based marketplace that connects waste generators with recyclers.  
Generators list recyclable waste, recyclers accept and pay (with a 5% platform fee charged to recyclers), and admin manages settlements and platform metrics.

## Tech Stack
- Frontend: React (Vite), Styled Components, React Router, Axios, React Toastify, React Icons
- Backend: Node.js, Express, MongoDB (Mongoose)
- Auth: Session-based (httpOnly cookies)
- Image hosting: Cloudinary

## Repo Structure (Monorepo)
backend/
frontend/
docs/


## Branch Workflow
- `main` → stable baseline only (protected)
- `develop` → active integration branch
- `feature/*` → feature branches merged into `develop` via PR
