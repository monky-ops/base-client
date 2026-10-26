Base Client
Base Client is a custom launcher and client for Minecraft: Java Edition, made by Monky (solo developer). It consists of two parts:

Base Client Launcher – a Windows desktop app (Java, JavaFX) that installs and starts Minecraft with Fabric.
Base Client mod – a single Fabric mod that brings the client features. It also runs in other Fabric launchers.
Status: in development. The launcher is waiting for approval to use the Minecraft services API.

Features
Own main menu with servers and worlds directly on the title screen, server banners and custom server looks
Client menu with dark/light mode, themes and selectable menu backgrounds
Minimap, world map and waypoints (can import shared Xaero waypoints from chat)
Schematic viewer with 3D preview and material lists for building projects
Launcher installs Minecraft, Fabric, the official Mojang Java runtime and keeps the mod up to date
Sign-in and privacy
Players sign in with their own Microsoft account to play the copy of Minecraft they own.

Standard Microsoft OAuth 2.0 authorization code flow with PKCE (public client, personal Microsoft accounts only, loopback redirect http://localhost, no client secret)
Then Xbox Live and XSTS authentication and login_with_xbox to get the Minecraft access token, then the player profile from the Minecraft services API
Tokens are stored only on the user's PC, encrypted with Windows DPAPI, and are sent only to Microsoft, Xbox Live and Minecraft services
No offline or shared accounts, no data collection, no telemetry
Disclaimer
NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.
