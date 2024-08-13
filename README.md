# DSharpPLus Template

This project is made using C# and [DSharpPlus](https://dsharpplus.github.io/DSharpPlus/).

## Setup

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/SniffBakaSniff/DSharpPLusTemplate
   cd DSharpPLusTemplate
   ```

2. **Install Dependencies:**
   Make sure you have the [.NET SDK](https://learn.microsoft.com/en-us/dotnet/core/install/windows) installed. If not, install it via your package manager.

   For Arch Linux:
   ```sh
   sudo pacman -S dotnet-sdk
   ```
   
   For Windows:
   
   [Download here](https://dotnet.microsoft.com/en-us/download)

3. **Configure your bot's token:**
   Create an environment variable named "DISCORD_TOKEN" in your system, with the value being your bot's token.	 

   In Windows this can be done by searching for "Edit the system environment variables", and in the window that pops up pressing "Environment variables...", "New..." and putting in the information.

   In Linux run the command ```export DISCORD_TOKEN=[your bot's token here]``` (Example: ```export DISCORD_TOKEN=1234567890```)

4. **Build the Project:**
   ```sh
   dotnet build
   ```

5. **Run the Bot:**
   ```sh
   dotnet run
   ```

Alternatively, you can open the project using [Visual Studio](https://visualstudio.microsoft.com/), which will handle everything except for step 1 and 3 for you. 

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.