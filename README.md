
# HopeChain-Daytona

HopeChain-Daytona is a Jetpack Compose Android project designed for transparent and secure donation tracking. This repository serves as a sample for creating Daytona workspaces for Android projects, utilizing Jetpack Compose and integrating blockchain technologies.

---

## 🚀 Getting Started

### Open Using Daytona
Follow these steps to set up and start working on the HopeChain-Daytona project using Daytona:

1. **Install Daytona**
   - Follow the [Daytona Installation Guide](https://github.com/daytonaio/daytona#installation) to set up Daytona on your system.

2. **Docker**
   - You should have to download Docker for isolating and configuration of the whole setup.
   
3. **Jetbrains Gateway**
   - To make a SSH connection between the project and the ide you need to have jetbrains gateway installed.
   [Jetbrains Gateway Installation Guide](https://www.jetbrains.com/remote-development/gateway/)

4. **Default IDE**
   - Choose Intellij Idea Ultimate as your default ide by the following command.
   ```bash
   daytona ide
   ```
5. **Create the Workspace**
   ```bash
   daytona create https://github.com/anuragkanojiya1/HopeChain-Daytona --builder=auto
   ```

6. **Open in IntelliJ IDEA Ultimate**
   - Daytona will automatically download and open the project in IntelliJ IDEA Ultimate with the required configurations and SDKs.
   
6. **Required Plugin**
   - Download Android plugin to configure android setup inside Intellij Idea Ultimate.

7. **SDKs**
   - Now to run the app on emulator,you should have to add a virtual device and its system image which will be available after android plugin get installed with android sdk.
---

## 📂 Project Structure
The repository contains the following components:
- **Jetpack Compose UI**: Fully composed UI designed for modern Android development.
- **Blockchain Integration**: Supports blockchain interactions using the Solana network.
- **Auto Builder Support**: auto-configured development container for consistent development environments.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```
