# Aviv Bryger

Materials scientist and electrochemist from the Technion: B.Sc. in Materials Science and Chemistry, M.Sc. in Chemistry (electrocatalysis).
Building tools that make labs more autonomous and everyday life a bit easier.

## What I'm interested in

- **Closing the loop in the lab**: from raw instrument files to clean data to a decision about the next experiment.
- **Electrochemistry and materials for energy**: electrocatalysts, electrolysis, characterization (XRD, TGA, electrochemical methods).
- **Tools that other researchers actually use**: simple interfaces on top of solid data processing.

## How I work

Automation is a means, not the goal. Every tool here started with a scientific question.

1. **Ask the question.** What do I actually want to learn, and which measurement would answer it?
2. **Design the experiment.** Which variables matter, and what data will it produce, how often and in what format?
3. **Find the manual work.** What is being done by hand, again and again? Where does data get stuck, or where do two people get different answers from the same data?
4. **Automate that part.** Turn raw instrument files into consistent, comparable data, and keep human judgment where it is really needed.
5. **Decide and ask again.** Use the results to choose the next experiment, and sharpen the question.

## Lab tools

- **[voltammetry-pipeline](https://github.com/Avivbryg/voltammetry-pipeline)**: takes cyclic voltammetry data from raw EC-Lab `.mpt` files to one row of metrics per cycle (peaks, charge, onsets, fixed-potential currents), so thousands of cycles can be compared across samples and anions.
- **[mpr-converter](https://github.com/Avivbryg/mpr-converter)**: opens binary EC-Lab `.mpr` files in the browser, plots them by cycle and exports CSV, TXT (for Origin) or Excel. Runs entirely in the browser, nothing is uploaded.

More analysis tools (XRD, TGA) coming soon.

## Contact

[aviv.bry@gmail.com](mailto:aviv.bry@gmail.com)
