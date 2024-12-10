
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
   - Set up JetBrains Gateway to establish an SSH connection between the project and your IDE.
   [Jetbrains Gateway Installation Guide](https://www.jetbrains.com/remote-development/gateway/)

4. **Set Default IDE**
   - Choose Intellij Idea Ultimate as your default ide by the following command.
   ```bash
   daytona ide
   ```
5. **Create the Workspace**
   - Run the following command to create a workspace:
   ```bash
   daytona create https://github.com/anuragkanojiya1/HopeChain-Daytona
   ```

7. **Open in IntelliJ IDEA Ultimate**
   - Daytona will automatically download and open the project in IntelliJ IDEA Ultimate, pre-configured with the necessary SDKs and tools.
   
8. **Required Plugin**
   - Install the Android plugin to configure the Android setup in IntelliJ IDEA Ultimate:
   
![Screenshot 2024-12-10 150555](https://github.com/user-attachments/assets/b996bc3a-a4d1-4eca-94a1-cd4a7ca2f703)
   - Open the Android SDK setup by clicking the directory icon.

![Screenshot 2024-12-10 151013](https://github.com/user-attachments/assets/e7c8250f-448e-45ce-b411-d4817e7c32ec)
![Screenshot 2024-12-10 151031](https://github.com/user-attachments/assets/4d5393ba-212e-4da8-86ed-292094c4433a)
   - Accept the license agreement and proceed.

![Screenshot 2024-12-10 151518](https://github.com/user-attachments/assets/7dcda1e6-a1cd-471b-9ea7-a9b174dbfddc)
![Screenshot 2024-12-10 152345](https://github.com/user-attachments/assets/ff3d0e65-7a53-4baf-b89c-0848e2194628)
![Screenshot 2024-12-10 152736](https://github.com/user-attachments/assets/1f51bc0f-ae67-40e4-8659-4aae84e7e49a)

   - After completing the steps outlined above, the Run and Devices section will appear at the top of your IntelliJ IDEA Ultimate interface.

![Screenshot 2024-12-10 153127](https://github.com/user-attachments/assets/8975b713-715f-4e9c-91e8-868a531cb916)

8. **Running the app**
   - Now to run the app on emulator, you should have to add a virtual device and its system image which will be available after android plugin get installed with android sdk.
   - Go to the device manager and then you can create a virtual device or can connect to your physical device to test the app.
     
![Screenshot 2024-12-10 153302](https://github.com/user-attachments/assets/1020650c-fe90-4906-b11f-e7cf16f8f54a)
   - Create a virtual device and download a system image.
     
![Screenshot 2024-12-10 153436](https://github.com/user-attachments/assets/521860cf-57ac-4295-9d0e-ff5128922fc2)
   - Or you can Connect with your physical device.
     
![Screenshot 2024-12-10 153534](https://github.com/user-attachments/assets/c5eafe53-729a-42be-ba08-a56b50bc6a00)
 - Note: Make sure you have enabled developer options to run the app on your android device.
   [Enable Developer Options](https://developer.android.com/studio/debug/dev-options)
---

## 📂 Project Structure
The repository contains the following components:
- **Jetpack Compose UI**: Fully composed UI designed for modern Android development.
- **Blockchain Integration**: Supports blockchain interactions using the Solana network.
- **Auto Builder Support**: auto-configured development container for consistent development environments.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
