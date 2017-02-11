# image-hosting-app
Instagram-like application utilizing Google Vision API

## Ruby on Rails
* Visually appealing modern UI (use some available solutions)
* Dashboard with a list of uploaded photos (tile and/or list)

### General aim

The aim of this task is to create a simple Instagram-like image hosting application that
additionally performs computer vision analysis via the Google Vision API and provides a visual
report on the uploaded photos showing what information was found.

### Raw list of features
* Adding/deleting photos
* Photo details view that includes:
  * Enlarged view of the selected photo
  * Simple visual presentation of computer vision results returned by the Google Vision API, e.g.:
  
### Google Vision API
Please register for a free version of the Google Vision API. The whole process is described
here: https://cloud.google.com/vision/docs/quickstart

The API returns a JSON report of the image analysis results. Please implement a simple visual
presentation of the results that will be shown on the photo -- check the “Try the API” section at
https://cloud.google.com/vision/ for inspiration.

### General notes

Use available solutions and external libraries wherever possible. Remember that the aim of this
task is to create a working application implementing all of the features described above given
the available time. However, make sure that you stick to the conventions and good practices.
