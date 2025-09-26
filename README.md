# WebApps Collection

This repository is a collection of web application code that has been deployed to Jekyll sites using customized layouts. Each web app is self-contained and ready for individual deployment.

## 📁 Repository Structure

This repository contains various web applications, each organized as standalone projects that can be easily deployed or modified.

## 🏷️ Naming Convention

All applications in this repository follow a consistent naming convention:

```
app-name - index.html
```

Where:
- `app-name` describes the functionality or purpose of the web application
- `index.html` is the main entry point for the application

## 🚀 Deployment to Jekyll Sites

These web applications have been designed to work with Jekyll sites using custom layouts:

1. Each app can be integrated into a Jekyll site by copying the relevant files
2. The custom layout templates handle the styling and structure
3. Apps are designed to be responsive and work across different Jekyll themes

## 📦 Individual Web App Deployment

To deploy any web application from this collection as a standalone app:

### Quick Start

1. **Copy the application files**:
   ```bash
   # Copy the desired app directory to your deployment location
   cp -r app-name/ /path/to/your/deployment/
   ```

2. **Modify as needed**:
   - Update configuration files
   - Customize styling and branding
   - Modify functionality to match your requirements

3. **Deploy**:
   - Upload to your web server
   - Or integrate into your existing web framework
   - Test functionality in your target environment

### Customization

Each web application is built to be easily customizable:

- **Styling**: Modify CSS files to match your brand
- **Functionality**: Update JavaScript files for custom behavior  
- **Content**: Edit HTML files to change text and structure
- **Configuration**: Update any config files for your environment

## 📝 Usage Examples

### For Jekyll Integration
```bash
# Copy app files to your Jekyll _includes or _layouts directory
cp app-name/index.html _includes/app-name.html

# Reference in your Jekyll pages
{% include app-name.html %}
```

### For Standalone Deployment
```bash
# Copy entire app directory
cp -r app-name/ ~/websites/my-new-app/

# Navigate and customize
cd ~/websites/my-new-app/
# Edit index.html, styles, and scripts as needed
```

## 🛠️ Development

When working with these applications:

1. **Test locally** before deployment
2. **Backup original files** before making modifications
3. **Document your changes** for future reference
4. **Test across different browsers** and devices

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Feel free to contribute additional web applications or improvements to existing ones. Please follow the established naming convention and ensure all apps are well-documented.
