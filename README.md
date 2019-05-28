# Anti ransomware

Anti ransomware application and mini-filter driver, log IRP operations in kernel mode to usermode for validation and handling

## Open issues

1. Define the detection module (before coding).
2. fix cpython to run python modules - define location to deploy
3. fix driver context : pid, path, time, IRP op, entropy, file id.
4. add traps recursivly by directory.
5. traps removing scheme
6. create alghoritm for adding traps at startup
7. improve gui
8. remedy plan - copy file to blob storage when write/rename/delete is done to it by untrusted process
9. calculation of entropy of file in case of write/rename/cleanup
10. model for counting files in system
11. kernel worker (work item) for calculating entropy
12. handle registry changes in kernel driver, we want to report registry changes also.
13. detect windows internel processess from all processess in kernel (kernel components)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc