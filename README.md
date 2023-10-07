smoothie's yEd Domain Driven Design Templates
=============================================

[yEd Graph Editor](http://www.yworks.com/en/products/yfiles/yed/) is a tool for creating and
visualizing diagrams, simplifying complex information for better communication.

And Domain-Driven Design (DDD) is a way of organizing and designing software that focuses on
understanding and modeling the real-world problem or "domain" that the software is meant to solve.

This repository offers DDD-related palettes and templates designed for use with yEd Graph Editor.

## Installation

You have a couple of options for installation. You can either clone or download the entire
repository, or you can download specific template/palette files that you wish to use.

```shell

git clone git@github.com:smoothie/yed-ddd-templates

```

**Note about Fonts**

Most of my templates and palettes use the Google Font "Mulish." You can either install the required
fonts from the "./fonts" directory or obtain [Mulish](https://fonts.google.com/specimen/Mulish)
directly from Google Fonts.

Alternatively, you can modify the `fontFamily` in the ".graphml" files to suit your preferences.

## Usage

To use these templates and palettes in yEd Graph Editor, follow these steps:

- Inside yEd, go to "Edit" > "Manage Palette..."
- Select "Import Section..."
- In the file dialog, select all the `.graphml` files and click "Okay"

This process will override any sections with the same names in yEd.

More info can be found at the
official [documentation](https://yed.yworks.com/support/manual/palette_manager.html).

## List of Palettes

| Palettes      | Shapes                                                                                                                              | Link                                                              |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|
| EventStorming | Domain Event, Command, Actor, External System, Question, Policy, Aggregate, Read Model, UI, Swimlane, Pivotal Line, Bounded Context | [DDD - EventStorming](./palettes/DDD%20-%20EventStorming.graphml) |

## Helpful Resources

- Getting started with
  DDD: [Starter Modelling Process](https://github.com/ddd-crew/ddd-starter-modelling-process) by
  DDD-Crew
- [EventStorming Glossary & Cheat Sheet](https://github.com/ddd-crew/eventstorming-glossary-cheat-sheet)
  by DDD-Crew

## Contributing

Contributions are one thing that make the open source community such an amazing place to learn,
inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull
request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## License

This project is licensed under the MIT - see the [LICENSE](./LICENSE) file for details.
