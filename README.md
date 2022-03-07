# Google APIs IP Ranges
IP ranges for Google APIs not including those available to GCP customers 

# Huh?
Google provides two lists of IP ranges; an exhaustive list of all Google IP ranges and a list of IP ranges available to their customers on Google Cloud Platform. They do not provide a list of Google-only ranges but instead suggest you [compute it subtractively](https://cloud.google.com/vpc/docs/configure-private-google-access#ip-addr-defaults). This repo contains a script to do so and a job that runs daily to maintain a [publicly available list of these ranges](https://storage.googleapis.com/ip-ranges/googleapis.txt).

# Wait...
It probably makes more sense to do this yourself, as it would take almost as much code to determine if this list is trustworthy. This is mostly for my personal use.
