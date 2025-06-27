# Durham mathematics modules

This project is an interactive tool for exploring and planning mathematics modules at Durham University. It allows students to select modules, view prerequisites, check for exclusions and ensure their selections meet departmental rules (such as credit limits and list requirements).

## Features

- **Interactive module selection**: Mark modules as completed or planned.
- **Automatic prerequisite checking**: Modules unlock as you meet their prerequisites.
- **Exclusion logic**: Modules that cannot be taken together are clearly marked and locked.
- **Credit tracking**: Warnings appear if you exceed 120 credits per level.
- **Clash enforcement**: For Level 3 and 4, ensures modules can't be picked from clashing lists.
- **Faculty handbook links**: For non-MATH modules, directs you to the official handbook for requirements.
- **Mobile-friendly design**.

## Usage

1. **Choose your entry year** on the main page.
2. **Select modules** you have completed or wish to take.
3. **Review warnings** for prerequisites, exclusions, and credit limits.
4. **Consult your academic advisor** for official guidance.

## Development

- All module data is stored in JSON files (e.g., `modules-2022-23.json`).
- The main interface is built with HTML, CSS, and vanilla JavaScript.
- To run locally, simply open `index.html` in your browser.

## Feedback & contributions

For technical issues, bug reports, or feature requests, please raise an issue here or submit a pull request. **Contributions are welcome!**

---

*This tool is experimental and not an official university resource. Always consult the [faculty handbook](https://apps.dur.ac.uk/faculty.handbook/) and your academic advisor for definitive module information.*

