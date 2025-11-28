🛡️ Military Units Path System

A visualization and path-restriction logic demo

This project demonstrates a map-based movement system for military units.
Each unit type (tank, plane, infantry, building, artillery) has its own movement and connection rules that define which units it can link to.

📌 Key Features

Each unit has predefined rules describing which other units it can connect to:

Unit	Can Connect To	Special Rules
Tank	Infantry, Building, Artillery	❌ Cannot connect to Plane
Plane	All units	✈️ Can connect to everyone
Infantry	Tank, Building, Artillery	❌ Cannot connect to Plane
Building	—	🛑 Cannot connect to anyone
Artillery	Tank, Infantry, Building	❌ Cannot connect to Plane

These rules are automatically enforced when adding or linking units on the map.

git clone https://github.com/gorstepanyan004-gif/my_project_2/Trajectoria Map.git
cd your-repo-name
start index.html     # Windows
open index.html      # MacOS

📜 License

MIT License — free for personal and commercial use.
