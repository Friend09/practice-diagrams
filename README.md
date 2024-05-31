# README: Mermaid

## To Create Mermaid Chart from a Mermaid File

### Pre-requisites

- Ensure you have the [mermaid CLI](https://github.com/mermaid-js/mermaid-cli) installed.
- Install using npm with the following command:
  ```sh
  npm install -g @mermaid-js/mermaid-cli
  ```

### Steps to Create a Mermaid Chart

1. Create a new file named `filename.mmd`.
2. Enter your Mermaid code into this file. For example:

   ```mermaid
   flowchart LR
       a --> b & c --> d
   ```

   NOTE: No need to include `mermaid` block if working inside `.mmd` file

3. Open the terminal and navigate to the folder containing your `.mmd` file.
4. Run the following command to generate an SVG file from your Mermaid file:
   ```sh
   mmdc -i <path>/input.mmd -o <path>/output.svg
   ```

## BOOKs & Resources

- [Creating Software with Modern Diagramming Techniques](https://learning.oreilly.com/library/view/creating-software-with/9798888650219/)
