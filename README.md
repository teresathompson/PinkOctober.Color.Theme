# PinkOctober.Color.Theme NuGet Package

## Overview

<img src="https://i.imgur.com/tPXxHJM.png" title="source: imgur.com" width="70"/>  

The PinkOctober.Color.Theme NuGet package offers a visually appealing pink color palette to enhance the aesthetics of your applications. With a soft and vibrant pink color scheme, this theme adds a touch of elegance and warmth to your user interfaces.

Breast Cancer Awareness Month often uses pink as a symbol of hope and support. By using this PinkOctober.Color.Theme, you can show your support for this important cause while creating beautiful and engaging user experiences.

## Features

- **Eye-Catching Pink Colors**: A carefully crafted pink color palette designed to catch the eye and create a pleasant visual experience. All the colors in this theme were tested for accessibility and contrast to ensure that they meet the [WCAG 2.0 AA](https://www.w3.org/TR/WCAG20/) standard.
- **Easy Integration**: Simple installation and integration into your project, with predefined styles and resources for various UI elements.


## Installation

To integrate the PinkOctober.Color.Theme into your project, follow these easy steps:

1. Install the NuGet package using your preferred package manager:

   ```
   Install-Package PinkOctober.Color.Theme
   ```

2. In your application's XAML files, merge the Pink Color Theme Resource Dictionary:

  ```xml
  <Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <XamlControlsResources xmlns="using:Microsoft.UI.Xaml.Controls" />
                <!-- Other merged dictionaries here -->
                <ResourceDictionary Source="ms-appx:///PinkOctober.Color.Theme/Theme/PinkOctoberResourceDictionary.xaml"/>
            </ResourceDictionary.MergedDictionaries>
            <!-- Other app resources here -->
        </ResourceDictionary>
    </Application.Resources>
   ```

3. Start applying the pink-themed styles and resources to your UI elements.

## Usage

Once you have referenced the package in the App.xaml file, the pink theme will apply to all components. 


## Examples

Here's an example of how the PinkOctober.Color.Theme can be applied to a simple button:

```xml
<Button Style="{StaticResource AccentButtonStyle}">Click Me</Button>
```
<img src="https://i.imgur.com/JLxPjaNm.png" title="source: imgur.com" />

ListView with PinkOctober.Color.Theme:

<img src="https://i.imgur.com/5rd7CoKm.png" title="source: imgur.com" />

## Credits

This PinkOctober.Color.Theme is inspired by Breast Cancer Awareness Month, and we encourage you to use it to show your support for this important cause.

## License

This package is licensed under the [MIT License](LICENSE.md).

## Support or Contact

If you have any questions, suggestions, or encounter any issues with this NuGet package, please feel free to [open an issue](https://github.com/teresathompson/PinkOctober.Color.Theme/issues) on GitHub or contact us at [teresaanne0101@gmail.com].


