# qr_code-generate
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>QR Code Generator</h1>
    <hr>
    <h2>Overview</h2>
    <p>This Python application generates QR codes for any given website link. It's simple to use and customizable, allowing you to specify the version, size, and border of the QR code.</p>
    <h2>Requirements</h2>
    <ul>
        <li>Python 3.x</li>
        <li>qrcode library</li>
    </ul>
    <h2>Installation</h2>
    <p>To use this QR Code Generator, you need to install the qrcode library if you haven't already. Run the following command:</p>
    <code>pip install qrcode[pil]</code>
    <h2>Usage</h2>
    <ol>
        <li>Run the script.</li>
        <li>Enter the website link when prompted.</li>
        <li>Specify the QR code version (1-40).</li>
        <li>Choose the box size for the QR code.</li>
        <li>Set the border size for the QR code.</li>
    </ol>
    <p>After these steps, the QR code will be generated and saved as ‘qr_code.png’ in the current directory.</p>
</body>
</html>
