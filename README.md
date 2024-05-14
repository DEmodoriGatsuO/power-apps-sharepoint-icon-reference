# SharePoint File Icon Reference Power App

This repository contains a Power App designed to demonstrate how to reference file icons from SharePoint. The app allows users to view and use SharePoint file icons in their Power Apps projects.

## Purpose

The primary purpose of this app is to:
- Provide a demonstration of how to reference and display file icons from SharePoint in Power Apps.
- Serve as a guide for Power Apps developers looking to incorporate SharePoint file icons into their applications.
- Enhance the visual representation of files in Power Apps by leveraging SharePoint's icon set.

## Features

- **Icon Reference**: Retrieve and display file icons from SharePoint.
- **File Type Recognition**: Automatically recognize and display the correct icon based on file type.
- **Customization**: Adjust the display settings of the icons to fit the app's design.

## Installation

To install and use the SharePoint File Icon Reference Power App:

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/sharepoint-file-icon-reference-power-app.git
   cd sharepoint-file-icon-reference-power-app
   ```

2. **Import the App into Power Apps**
   - Go to [Power Apps](https://make.powerapps.com/).
   - Click on "Apps" and then "Import canvas app".
   - Upload the `.msapp` file from the repository.

3. **Set Up SharePoint Connection**
   - Ensure you have a SharePoint site with document libraries.
   - Create a connection to your SharePoint site within Power Apps.
   - Modify the app to point to your specific SharePoint site and document library if needed.

4. **Run the App**
   - Once imported and configured, you can run the app directly from Power Apps.

## Usage

1. Open the SharePoint File Icon Reference app.
2. Browse through the different file types and see the corresponding SharePoint icons.
3. Use the app as a reference for implementing similar functionality in your own Power Apps.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
   ```sh
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes.
   ```sh
   git commit -m "Add your feature description"
   ```
4. Push to your branch.
   ```sh
   git push origin feature/your-feature-name
   ```
5. Open a pull request with a detailed description of your changes.

## Power Fx
```plaintext
"$""https://static2.sharepointonline.com/files/fabric/assets/item-types/24/{Coalesce(
    ThisItem.Value,
    ""genericfile""
)}.svg"""
```

```plaintext
$"https://static2.sharepointonline.com/files/fabric/assets/item-types/24/{Coalesce(
    ThisItem.Value,
    "genericfile"
)}.svg"
```
