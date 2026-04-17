example target 
https://enfor cement tracker.com/data4sfk3j4hwe324kjhfdwe.json?_=1776010803830

that random string in the filename (data4sfk3...json) is a security measure. The web admins likely rotate that filename every few weeks or months to stop people from doing exactly what we are about to do.

the fetcher script dynamically reads the homepage first to find whatever the current secret filename is, generates a fresh cache-buster, downloads the whole database, and saves it as a CSV
