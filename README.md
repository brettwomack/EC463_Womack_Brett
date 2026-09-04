# 01-Individual Repo
Template for individual student repo

<img src="./images/Headshot.png" width="20%">
<p> Replace this image with your headshot photo</p>

## Individual links
- [Log book]()
- [Individual Google Drive Folder]()

## Team links
- [Team Google Drive folder]()
- [Team Board]()

## Organization of this repo

This depends on your role as an engineer. Try these queries to set up
your initial repo. You can always change this later.

- "What is a good organization of a repo for an (Electrical|Computer|Mechanical Engineer) in a software-electronics-mechanical project?"

You can customize your based on your preferred tools (e.g., CAD
software, IDE, etc.)

Example:

```
my-project/
├── .github/                # CI/CD workflows, issue templates, and pull request templates
├── docs/                   # General documentation, images, and user manuals
├── mechanical/             # CAD files, drawings, and simulations
│   ├── cad/                # Source files (.sldprt, .step, .f3d)
│   ├── drawings/           # 2D manufacturing drawings (.pdf, .dxf)
│   └── simulations/        # FEA or CFD analysis files
├── electronics/            # Schematics, PCBs, and BOMs
│   ├── schematics/         # Schematic files (.sch, .kicad_sch)
│   ├── pcb/                # Board layouts (.kicad_pcb, .brd)
│   ├── gerbers/            # Manufacturing gerber files and drill files
│   └── bom/                # Bill of Materials (.csv or spreadsheet)
├── software/               # Code for firmware, companion apps, or scripts
│   ├── firmware/           # Microcontroller source code (STM32, ESP32)
│   ├── host/               # Companion software (Python scripts, GUI, mobile app)
│   └── tests/              # Automated tests or test scripts
├── .gitignore              # Files and folders for Git to ignore
└── README.md               # Main project overview, setup guide, and quickstart

```
