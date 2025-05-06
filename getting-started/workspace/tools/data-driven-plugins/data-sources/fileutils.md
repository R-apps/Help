---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# FileUtils

The "FileUtils" plugin offers a range of file operations that can help simplify your file management tasks. Whether you need to copy, delete, encrypt, or resize files, the File Utils plugin has you covered. With its easy-to-use interface and powerful functionality, managing your files has never been easier!

Let's look at each utility.

#### Get Properties

This retrieves a file's properties from the selected file directory. You can choose which properties to get, such as the size, the date it was created, the date it was last changed, and more. If the properties in your selection have to do with dates, you can tell the plugin what format to use to get them.

{% hint style="info" %}
**Tip**: If you choose the file source in the Plugin Configuration, you only need to specify the file name in the Input Configuration; otherwise, give the file's absolute path for the "inputFile" attribute.
{% endhint %}

It's helpful when you need to get specific information about a file before doing any further operations so that you can handle data correctly.

**Copy File to Directory**

This service duplicates a specified file from the source file directory and places it in the destination file directory.

It is handy when creating backups, organizing files, or when you need identical copies in different locations.

#### Delete File

This service instantly deletes a file in the specified file directory.

It comes in handy when you need to delete a file but don't have access to it.

#### **Move File to Directory**

This transfers a file seamlessly from a specified file directory to a different file directory.

It is useful when reorganizing files or ensuring files are stored in a more relevant location.

#### **Rename File**

This service lets you effortlessly rename a file in the specified file directory.

It's useful when you need to delete a file without accessing it.

#### Compress Files

This compresses multiple files into a single archive (ZIP, RAR, TAR, or GZ). These files can be dynamic These files can be dynamic (for example, documents uploaded by a user when submitting a form) or static. To compress static files, specify the no. of files and their paths. You can even choose to store the compressed file in a different file directory.

This is useful for archiving files or transferring multiple files at once.&#x20;

#### Decompress file

This lets you extract files out of a compressed archive (ZIP, RAR, TAR, or GZ) in the chosen file directory and put them in the same or a different file directory.&#x20;

It is necessary when sending or receiving compressed files so you can get to their contents.

#### Encrypt file

This lets you add an extra layer of protection to the contents of a file from a specific file source. This encryption is done with the encryption format and the key you choose. You can even choose to have a different name for the encrypted file and place it in a different file directory.

It's often used when dealing with sensitive information, ensuring data privacy and security.

#### Decrypt file

This service lets you decrypt files that have previously been encrypted. This decryption is done with the decryption format and the key you choose. You can even choose to have a different name for the decrypted file and place it in a different file directory.

It's ideal when dealing with confidential information.

#### Make as read-only

This service makes a file read-only, preventing any changes from being made to it.

It is useful to safeguard important files from any changes or edits.

#### Remove read-only

This removes the read-only attribute from a file.&#x20;

Use it to remove the read-only restriction from a file when you need to make modifications to it.

#### File to string

This converts the file content into a string format.

It's helpful when dealing with text-based files or when you need to manipulate file content as a string.

#### File to Base64

This converts the file contents to a Base64-encoded string.

It helps you embed the file content into any text documen&#x74;_,_ such as HTML, JSON, or XML. This is often used in applications involving data transmission, secure data storage, or content sharing.&#x20;

#### Image to Base64

This converts an image into Base 64, an ASCII text format.

It helps in embedding image data within other formats like HTML, CSS, or JSON. This can reduce the number of HTTP requests as the data is loaded at the same time as the webpage.&#x20;

#### Base64 to Image

This decodes a Base64-encoded string back into an image file.

Essential for applications dealing with Base64-encoded images, ensuring seamless image handling.

#### Write String to file

This conversion writes a specified string into a file. You can use this conversion to store data in a file.

It is useful for applications involving this conversion and storing it in a file.

#### Write Base64 to file

This conversion writes a Base64-encoded string into a file.

It is ideal for applications involving Base64-encoded data storage, ensuring efficient file creation.

#### Replace all the specified content in the file

This replaces the specific content (only text) within a file.

It is handy when updating information or correcting errors across multiple instances in a file.

#### Create new directory

This utility establishes a new directory (folder) within the file system.

It is useful when organizing files and creating a structured hierarchy without accessing the database.

#### Image compress

This allows you to shrink an image to a specific height, width, and compression quality while maintaining image quality.

It is useful for optimizing images for web pages, emails, or applications with size constraints.

#### Image resize

This helps you resize an image to a specified height and width without compromising its quality.

It is helpful when specific image size requirements are necessary for display or storage.

#### Get Files & Folders List

This retrieves a list of files and folders within a specified directory.

It is useful for applications that require dynamic file system navigation or cataloging.

### How to Use?

Drag the plugin into your API flow. Choose the file operation and the file source. Specify the necessary input file(s) or give the absolute paths in the Input Configuration, and set up the parameters in the Output Configuration to get the status.
