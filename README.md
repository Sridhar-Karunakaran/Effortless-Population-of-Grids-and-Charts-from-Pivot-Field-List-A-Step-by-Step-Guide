# Effortless Population of Grids and Charts from Pivot Field List: A Step-by-Step Guide


## Overview
This project showcases best practices for integrating server-side pivot field list functionality with client-side grid and chart rendering. It provides a complete example of how to build data-driven applications that allow users to dynamically configure and visualize data through pivot controls. The solution combines ASP.NET Core backend services with HTML5 and JavaScript frontend technologies for a seamless data visualization experience.

## Features
- **Server-Side Pivot Field List**: Leverages a robust server-side pivot component for efficient data handling
- **Dynamic Grid Population**: Automatically populates data grids based on pivot configurations
- **Interactive Charts**: Renders visual charts alongside grid data for comprehensive data analysis
- **Real-Time Data Rendering**: Updates grids and charts in real-time as pivot settings change
- **Cross-Platform Compatibility**: Built with standard web technologies for broad browser support

## Prerequisites
Before running this application, ensure you have the following installed:
- **Visual Studio 2022** or later (Community, Professional, or Enterprise edition)
- **.NET 8.0 SDK** or compatible runtime
- **NuGet Package Manager** (included with Visual Studio)
- A modern web browser (Chrome, Firefox, Edge, or Safari)

## Installation & Setup

Follow these steps to run the application:

1. **Open the Project**
   - Open the [PivotController](./PivotController/) solution in Visual Studio

2. **Restore Dependencies**
   - Dependent packages will be downloaded automatically from nuget.org upon opening the project
   - Visual Studio will restore all required NuGet packages during the build process

3. **Build and Run the Application**
   - Build the solution in Visual Studio
   - Run the application once the packages are downloaded

4. **Configure the Client URL**
   - Once the application is hosted locally, copy the localhost URL from the browser or Visual Studio output
   - Paste this URL into the **Sample->pivot.js** file in the appropriate configuration variable

5. **View the Results**
   - Open the **Sample->pivot.html** file in your web browser
   - The pivot field list will be populated with data, displaying interactive grids and charts

## Usage
The application automatically handles the communication between the server-side pivot control and the client-side visualization components. Simply follow the setup steps above, and the grid and chart will render with sample data from the server.
