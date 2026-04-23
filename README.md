# CS 340 - Project Two Portfolio Artifact

**Student Name:** Rimon Hamo  
**Course:** CS 340 Client/Server Development  
**Date:** April 23, 2026

---

## Project Two Artifacts

**Repository Link:** [CS340-Project-Two](https://github.com/rayhamo98/CS340-Project-Two)  
*(Replace the link above with your actual repository URL)*

### Files Included:
- `app.py` – Main Grazioso Salvare Animal Rescue Dashboard
- CRUD Python Module (database operations)
- Dashboard screenshots / outputs
- Module Eight Assignment Document

---

## Reflection Questions

### 1. How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by using **modular design**, clear naming conventions, proper comments, and separating concerns. 

In Project One, I developed a reusable **CRUD Python module** that handled all MongoDB operations (Create, Read, Update, Delete). In Project Two, I imported this module into the Dash dashboard instead of writing database code directly in the main file. 

**Advantages:**
- The dashboard code stayed clean and focused on the user interface.
- Changes to database logic only need to be made in one place.
- The CRUD module can be easily reused in future projects.

This approach makes the code much easier to maintain, debug, and adapt for other clients in the future.

### 2. How do you approach a problem as a computer scientist?

As a computer scientist, I approach problems by first **understanding the client’s requirements**, breaking them into smaller tasks, and then designing a modular solution.

For Grazioso Salvare’s dashboard, I analyzed the needed features (animal filtering by rescue type, interactive charts, and data table). I used the **MVC pattern** (Model = CRUD module, View = Dash layout, Controller = callback functions). 

This project was different from previous assignments because it required integrating **Python, Dash, MongoDB, and Plotly** into one functional web application. 

In the future, I will continue using requirement analysis, modular programming, and iterative testing when building applications or databases for clients.

### 3. What do computer scientists do, and why does it matter?

Computer scientists solve real-world problems by designing efficient systems that turn data into useful information. 

The dashboard I built for Grazioso Salvare helps their staff quickly filter and visualize animal rescue data. This allows them to make faster and better decisions when selecting dogs for training programs. 

This type of work matters because it increases operational efficiency, reduces manual workload, and directly supports the organization’s mission. It shows how software development can create real positive impact for companies and communities.

---

**Thank you for reviewing my CS 340 Portfolio Artifact.**
