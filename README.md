 # wca-ai-tool-alpha

 ## Project Overview
 **wca-ai-tool-alpha** is an AI-powered Python tool designed to automate the drafting of professional emails. By utilizing the **R-T-C-C-O framework**,   the tool ensures that every generated email has a clear role, task, and objective, specifically tailored for the Kenyan professional context.

 ## Features
 * **Python-based logic**: Runs directly from the command line interface.
 * **API Integration**: Connects to the **Claude-3 Haiku** model via the Anthropic API for fast and efficient generation.
 * **R-T-C-C-O Prompting**: Built-in instruction design (Role, Task, Context, Constraint, Objective) ensuring high-quality and structured output.
 * **JSON Handling**: Properly parses API responses into a clean and readable format for the user.

## Installation and Setup

1. Clone the repository and open its root directory.

   ```bash
   git clone https://github.com/WhyteRosee/wca-ai-tool-alpha.git
   cd wca-ai-tool-alpha
   ```

2. Create a virtual environment and activate it.

   On macOS or Linux:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

   On Windows Command Prompt:

   ```bat
   py -m venv .venv
   .venv\Scripts\activate.bat
   ```

3. Install the pinned dependencies.

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Create a `.env` file in the repository root and replace `your_api_key_here` with your Anthropic API key.

   ```dotenv
   ANTHROPIC_API_KEY=your_api_key_here
   ```

5. Run the chatbot from the repository root.

   ```bash
   python chatbot.py
   ```

### Group members
 
 - Felix Odhiambo 
 - Nicholas Murithi
 - Lakeisha Warigia
 - Nicole Hellen
 - Joseph Juma
  
  
 
