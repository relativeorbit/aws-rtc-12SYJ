# AWS RTC STAC Generator

[![STAC Browser](https://github.com/relativeorbit/aws-rtc-stac/actions/workflows/browse.yml/badge.svg)](https://github.com/relativeorbit/aws-rtc-stac/actions/workflows/browse.yml)
[![STAC Updater](https://github.com/relativeorbit/aws-rtc-stac/actions/workflows/update.yml/badge.svg)](https://github.com/relativeorbit/aws-rtc-stac/actions/workflows/update.yml)
[![STAC Validator](https://github.com/relativeorbit/aws-rtc-stac/actions/workflows/validate.yml/badge.svg)](https://github.com/relativeorbit/aws-rtc-stac/actions/workflows/validate.yml)
[![badge](https://img.shields.io/static/v1.svg?logo=Jupyter&label=PangeoBinder&message=AWS+us-west-2&color=orange)](https://aws-uswest2-binder.pangeo.io/v2/gh/pangeo-data/pangeo-docker-images/2021.09.30?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Frelativeorbit%252Faws-rtc-stac%26urlpath%3Dlab%252Ftree%252Faws-rtc-stac%252F%26branch%3Dmain) 

This is a template repository with some GitHub Actions to facilitate on-demand generation of static STAC Catalogs for Analysis Ready Sentinel-1 Backscatter Imagery, on the [AWS Public Data Registry](Analysis Ready Sentinel-1 Backscatter Imagery). The goal is to create STAC for a specific MGRS square so that you can easily visualize it and open a notebook to do some custom analysis with Xarray.

1. Click 'Use this template'
1. Go to the 'Actions' tab of your new repository
1. Run the workflows to add STAC
1. See note below on setting up a STAC Browser webpage


## STAC Browser via GitHub pages

1. Go to Settings-->Pages--gh_pages to enable serving Github Pages
1. Run the STAC Browser GitHub Action
1. Go to the corresponding website for the repository: https://relativeorbit.github.io/aws-rtc-stac/
