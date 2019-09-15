# MvvmCross WebBrowser Plugin
![GitHub](https://img.shields.io/github/license/SByteDev/Net.MvvmCross.Plugins.WebBrowser.svg)
![Nuget](https://img.shields.io/nuget/v/SByteDev.MvvmCross.Plugins.WebBrowser.svg)

[![Build Status](https://travis-ci.org/SByteDev/Net.MvvmCross.Plugins.WebBrowser.svg?branch=master)](https://travis-ci.org/SByteDev/Net.MvvmCross.Plugins.WebBrowser)
[![codecov](https://codecov.io/gh/SByteDev/Net.MvvmCross.Plugins.WebBrowser/branch/master/graph/badge.svg)](https://codecov.io/gh/SByteDev/Net.MvvmCross.Plugins.WebBrowser)
[![CodeFactor](https://www.codefactor.io/repository/github/sbytedev/net.mvvmcross.plugins.webbrowser/badge)](https://www.codefactor.io/repository/github/sbytedev/net.mvvmcross.plugins.webbrowser)

Provides a cross-platform UI for displaying the web page.

## Installation

Use [NuGet](https://www.nuget.org) package manager to install this library.

```bash
Install-Package SByteDev.MvvmCross.Plugins.WebBrowser
```

## Usage
```cs
using SByteDev.MvvmCross.Plugins.WebBrowser;

await Mvx.IoCProvider.Resolve<IMvxWebBrowser>().ShowWebPageAsync(new Uri("https://github.com"), CancellationToken.None);
```

## Implementation
Based on [Xamarin WebBrowser Plugin](https://github.com/SByteDev/Net.Xamarin.Plugins.WebBrowser).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update the tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
