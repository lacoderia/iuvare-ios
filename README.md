# Iuvare iOS App

This iOS app is a wrapper for an existing website.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Iuvare's repository contains a swift project, so `Xcode 11 or later` version is needed.

### Installing

Clone iuvare-ios repository

## Running

1. Open `iuvare-ios.xcodeproj` file
2. Build and run

## Deployment

1. Update bundle version and build info
2. Create the archive file
```
Product -> Archive
```
3. Export archived file with `Xcode Application Loader`
4. Upload file to iTunes Connect via `Transporter App`

## Troubleshooting

#### Error while uploading file to iTunes Connect via Application Loader

Error: No suitable application records were found. Verify your bundle identifier is correct

This problem might appear due to wrong develop team credentials on the Application Loader app. To avoid this error, the `Transporter App`should be used to upload the desired file to iTunes Connect.
