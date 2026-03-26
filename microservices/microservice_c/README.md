# Image Microservice

Service that handles product image storage and delivery for the Catalog Website.
It accepts uploads, serves original files, and exposes image metadata so other services and the UI can reliably reference product media.

Used for
- Uploading and storing product images
- Serving originals to clients and downstream services
- Exposing image metadata (filename, MIME type, size, tags, timestamps)
- Admin-protected create/delete operations via a shared token
- Centralizing media handling behind a simple HTTP interface

---

Setup & Run
Install dependencies: npm install

Start the service: node image_controller.mjs

Localhost
- Base URL: http://localhost:4004
