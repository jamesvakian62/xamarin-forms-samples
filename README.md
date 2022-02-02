# Xamarin, iOS / Andriod, app builds

# Top and Bottom Menu app display

# Single CodeBase

#![Simulator Screen Shot - iPad Pro (12 9-inch) (5th generation) - 2022-02-02 at 10 01 02](https://user-images.githubusercontent.com/95377031/152217337-e6d752fd-38be-4d07-922a-8d741ca883f7.png)
![Simulator Screen Shot - iPad Pro (12 9-inch) (5th generation) - 2022-02-02 at 10 01 34](https://user-images.githubusercontent.com/95377031/152217340-cc4c904d-642d-4ae6-9275-eceb662a691c.png)
![Simulator Screen Shot - iPod touch (7th generation) - 2022-02-02 at 09 25 37](https://user-images.githubusercontent.com/95377031/152217344-db3b3b46-c7a4-4c1e-87be-1c2439a05fdc.png)
![Simulator Screen Shot - iPod touch (7th generation) - 2022-02-02 at 09 59 35](https://user-images.githubusercontent.com/95377031/152217348-37439a60-fd9e-4bdd-944d-d2d751928774.png)
![Simulator Screen Shot - iPod touch (7th generation) - 2022-02-02 at 09 59 39](https://user-images.githubusercontent.com/95377031/152217349-687779c3-335b-4df0-af71-7b47d460d559.png)
![Simulator Screen Shot - iPod touch (7th generation) - 2022-02-02 at 09 59 44](https://user-images.githubusercontent.com/95377031/152217350-19af6918-887c-48f2-b021-c2ee462b1ec0.png)
![Simulator Screen Shot - iPod touch (7th generation) - 2022-02-02 at 10 00 03](https://user-images.githubusercontent.com/95377031/152217352-0573c3c3-8592-4b05-9116-efd67948e5a7.png)


# Forms Gallery

# Xamarin.Forms code samples

The samples in this repository demonstrate how to use different aspects of Xamarin.Forms to build cross-platform apps for iOS, Android, and the Universal Windows Platform (UWP). Please visit Microsoft [code sample browser](https://docs.microsoft.com/samples/browse/?term=Xamarin.Forms) to download individual samples.

For additional platform support, visit the following forks:

- Tizen: https://github.com/Samsung/xamarin-forms-samples 
- GTK#: https://github.com/jsuarezruiz/xamarin-forms-samples/tree/gtk

## License

See the [license file](LICENSE) and any additional license information attached to each sample.

## Sample submission guidelines

This repository welcomes contributions and suggestions. If you want to create a new sample, you need to work with an employee to help bring the new sample into the repository. Start by raising a [GitHub issue](https://github.com/xamarin/xamarin-forms-samples/issues/new) in this repository that outlines your proposed sample. Please note that samples in the `master` branch of this repository shouldn't rely on preview or pre-release NuGet packages.

The Xamarin.Forms samples in the [Microsoft samples browser](https://docs.microsoft.com/samples/browse/?term=Xamarin.Forms) are sourced from this repository. Samples need to comply with the following requirements:

- **Screenshots** - a folder called Screenshots that has at least one screen shot of the sample on each platform (preferably a screen shot for every page or every major piece of functionality). For an example of this, see [TodoREST](https://github.com/xamarin/xamarin-forms-samples/tree/master/WebServices/TodoREST/Screenshots).

- **Readme** - a `README.md` file that explains the sample, and contains metadata to help customers find it. For an example of this, see [WebServices/TodoREST](https://github.com/xamarin/xamarin-forms-samples/blob/master/WebServices/TodoREST/README.md). The README file should begin with a YAML header (delimited by `---`) with the following keys/values:

  - **name** - must begin with `Xamarin.Forms -`

    - **description** - brief description of the sample (&lt; 150 chars) that appears in the sample code browser search

    - **page_type** - must be the string `sample`.

    - **languages** - coding language/s used in the sample, such as: `csharp`, `fsharp`, `vb`, `java`

    - **products**: should be `xamarin` for every sample in this repo

    - **urlFragment**: although this can be auto-generated, please supply a value that represents the sample's path in this repo, except directory separators are replaced with dashes (`-`).

    Here is a working example from [_WebServices/TodoREST_ README raw view](https://raw.githubusercontent.com/xamarin/xamarin-forms-samples/master/WebServices/TodoREST/README.md).

    ```yaml
    ---
    name: Xamarin.Forms - TodoREST
    description: This sample demonstrates a Todo list application where the data is stored and accessed from a RESTful web service.
    page_type: sample
    languages:
    - csharp
    products:
    - xamarin
    urlFragment: webservices-todorest
    ---
    # Heading 1

    rest of README goes here, including screenshot images and requirements/instructions to get it running
    ```

    > NOTE: This must be valid YAML, so some characters in the name or description will require the entire string to be surrounded by " or ' quotes.

- **Buildable solution and .csproj file** - the project _must_ build and have the appropriate project scaffolding (solution + .csproj files).

This approach ensures that all samples integrate with the Microsoft [sample code browser](https://docs.microsoft.com/samples/browse/?term=Xamarin.Forms).

If you have any questions, create an issue or ask on the [Xamarin Forums](https://forums.xamarin.com/).

