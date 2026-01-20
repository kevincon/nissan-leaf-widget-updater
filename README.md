> [!WARNING]
> This project is archived and is no longer being maintained, see [this blog post](https://kevintechnology.com/posts/leaf-widget-response/) for more information.

# Nissan Leaf Widget Updater

![GitHub License](https://img.shields.io/github/license/kevincon/nissan-leaf-widget-updater)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/kevincon/nissan-leaf-widget-updater/.github%2Fworkflows%2Fupdater.yml)](https://github.com/kevincon/nissan-leaf-widget-updater/actions/workflows/updater.yml)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/kevincon/nissan-leaf-widget-updater/main.svg)](https://results.pre-commit.ci/latest/github/kevincon/nissan-leaf-widget-updater/main)

> [!IMPORTANT]
> The NissanConnect® Application Terms of Use (contained in the app itself, effective January 23, 2018) state (**emphasis** mine):
>
> > The Sites, the App, or any of the content provided in the Site or the App, including, but not limited to, text, images, buttons, html code, audio and video, may not be copied, reverse engineered, reproduced, republished, uploaded, posted, transmitted or distributed without our prior written consent. You may not mirror any of the content from the Site on another website or in any other media. **You may, however, download, display, and/or print one copy of the Site or of the App, or a part thereof, for your personal, non-commercial use without modifying the content displayed from either the Site or the App, including all copyright, trademark, and other proprietary notices.**
>
> This repo is for educational/demonstrative purposes. I have no affiliation with Nissan and neither I nor the software may be held liable for any consequences resulting from its use.

This repo:

1. calls the [reusable GitHub Action](https://docs.github.com/en/actions/sharing-automations/creating-actions/about-custom-actions) from https://github.com/kevincon/nissan-connect-scraper to scrape information about my [Nissan LEAF®](https://en.wikipedia.org/wiki/Nissan_Leaf) vehicle from the [NissanConnect® Android app](https://play.google.com/store/apps/details?id=com.aqsmartphone.android.nissan)
1. sends that information to an [IFTTT applet](https://ifttt.com/explore/ifttt_applets) that displays it in a [IFTTT home screen widget](https://ifttt.com/explore/how-to-use-widgets-ios) on my iPhone

See [this blog post](https://kevintechnology.com/posts/leaf-widget/) for more information.
