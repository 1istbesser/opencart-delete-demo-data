# opencart-delete-demo-data

## Preview
![opencart-delete-demo-data-preview](/preview.png?raw=true "Preview image of the opencart delete demo data extension")

## Description

This extension makes it possible to easily delete all the demo data at once before going into production. The available options are all the data pieces included in the opencart clean installation.I will consider adding support for any other data/files that you may want to remove.

## Compatibility
3.x

Any opencart version newer than 3.0.0

## Installation
### Method 1 - Extension Installer
<ul>
  <li>Admin Panel</li>
  <ul>
    <li>Extensions</li>
    <ul>
      <li>Installer</li>
      <p>Upload the zip file version of the extension</p>
    </ul>
  </ul>
</ul>

### Method 2 - Manual Installation
<ol>
  <li>Clone the repository or unzip the archive file</li>
  <li>Move the following files from the upload folder to your project folder:</li>
  <ul>
    <li> upload/admin/controller/extension/module/remove_demo_data.php <b>-></b><br/>
         your-project/admin/controller/extension/module</li>
    <li> upload/admin/language/en-gb/extension/module/remove_demo_data.php <b>-></b><br/>
         your-project/admin/language/en-gb/extension/module</li>
    <li> upload/admin/view/stylesheet/remove_demo_data.css <b>-></b><br/>
         your-project/admin/view/stylesheet</li>
    <li> upload/admin/view/template/extension/module/remove_demo_data <b>-></b><br/>
         your-project/admin/view/template/extension/module</li>
  </ul>
</ol>

### Method 3 - Marketplace
Soon

## Usage

Find the extension: Admin panel -> extensions -> extensions ->  modules(choose from the dropdown list) -> Remove demo data module

If the extension has an install button and is not enabled, hit install

To use it, hit the edit button

On the Remove demo data page, you can see two columns, the first one is for database data and the second one is for files.

Check whichever components you want to delete the data from and/or the files and submit via the "Remove data" button at the bottom

That's all, your selected data has been deleted.

## Attention

Although this was created to delete all the demo data a fresh installation/development version of the opencart might have, please understand that it deletes all the data from the selected components, therefore, if you check categories, it will delete all categories, if you check products, it will remove all products and so on.
