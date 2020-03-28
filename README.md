# ProjectName

![Cover.img](/02%20-%20Export/Project%20overview/GitHub/Cover.png)

Please read the information below carefully. It has everything you and developers need to continue working on this project.

## Download links
- [Source file (.sketch)](/01%20-%20Sources/)
- [Logotype](/02%20-%20Export/Branding/Logotype/)
- [Icons](#Icons)

## Help

- Designer - Artem Attvud. Contacts - [Email](mailto:w@res.pm), [LinkedIn](https://www.linkedin.com/in/attvud)

## InVision

- Web Site - [Desktop](), [Mobile]()
- [Mobile App (Android)]()

InVision is the digital product design platform used to make the world's best customer experiences. Click the link and hold the `"shift"` button to see the interactive elements.

## Colors
![Colors.img](/02%20-%20Export/Project%20overview/GitHub/Colors.png)

[Here's the SCSS code](/X/Docs/color%20system.scss) that will create variables for the primary and secondary colors, as well as their shades, and add a palette for grayscale. It is important to use the specified grayscale.

Using this solution, you can easily create a behavior for elements (hover, focus, etc.) and refer to each color and its hue by a variable name.

## Typography

![Typography.img](/02%20-%20Export/Project%20overview/GitHub/Typography.png)

**Legend**: `R` - Regular, `B` - Bold, `LH` - Line Height. The font set used in the project is marked in blue.

Depending on the platform, you should use the following fonts:

- Web - Arial
- Android - Roboto
- iOS & macOS - SF Pro

**Be sure to use this CSS code in the web front-end**

```css
body {
    font-family: "-apple-system",BlinkMacSystemFont,Arial,sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

## Icons

![Icons.img](/02%20-%20Export/Project%20overview/GitHub/Icons.png)

All icons are optimized using the [SVGO](https://github.com/svg/svgo) API. The weight of the icons was reduced by 30-48%. Export settings are specified in [this file]().

Icons have been successfully tested on the following platforms: Web, Android, iOS.

All icons are divided into sections:

1. [Main icons.]() ≈ 1,000 icons named and divided by folders according to their value.
2. [Project icons]() (social networks, messengers, etc.).

## Technologies and software used

**UX/UI Design**

- [Sitis Design System (SDS)]() - Design System for this project
- Sketch - UX/UI & Prototyping
- InVision, YouTube – Demonstration of the result of work
- Principle, Flinto, InVision Studio – Animation
- Affinity Designer, Adobe Illustrator – Working with vector graphics
- Affinity Photo, Adobe Photoshop – working with raster graphics
- Github – work with sources, project support, feedback from developers
