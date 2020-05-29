# Create Machine Learning APP

Create Machine Learning apps with minimal setup.


This library does not solve machine learning tasks, it just reduces the burden of seting up your project and lets you focus on model development. 

*This library is totally inspired by [create-react-app](https://github.com/facebook/create-react-app).*. **Note:** We hope you don't get irritated by how much we draw inspiration from `create-react-app` it just a very inspiring project.

## Quick Overview

```
pip install create-ml-app
create-ml-app my-app
cd my-app
create-ml-app start-service
```

## Creating an app

To create a new Machine Learning app you just need to type the following command on your terminal:

```
create-ml-app my-app
```

It will create a directory called `my-app` inside the current folder. Inside that directory, it will generate the initial project structure:

```
my-app
├── README.md
├── .gitignore
├── src
│   ├──development
│      ├──model.py
│      ├──data.py
│      ├──evaluation.py
│      ├──report.ipynb
│   ├──deployment
│      ├──web
│      ├──embedded
```

Note that any template could deviate from this project structure so make sure you read through each teamplate's documentation. We expecte the `deployment` directory to vary a lot based on the technology stack being used. We release this project together with some curated templates, but our philosofy requires us to enforce as little as possible. 

## User Guide

You can find detailed instructions on using Create ML App in [its documentation]()

## Philosophy

- **Zero Dependecy:** This command line tool only gives you basic file structure. Each template will impose the dependencies for the use case they target.
- **No Configuration Required:** You don't need to configure anything. A reasonably good configuration both development and deployment should be given by the template you use. 
- **No Lock-In:** This project will only give you a basic file structure to keep your projects organized, but there could be many template implementations, each targeting a particular set of libraries, framework or deployment settings.
- **Machine Learning to Build Apps:** We acknowledge that the experimenting aspect of Machine Learning Engineering is quite a beloved feature, but is not the end of it. We use Machine Learning to build apps, whether they are a command line tool, an isolated web service (preffred) or a part of a larger server.

## Contributing

We would appreciate your effort to make this a great project by helping others to kickstart their machine learning apps. There are several ways of contributing, see [CONTRIBUTING.md](./CONTRIBUTING.md) for more information.

## Credits

This project exists thanks to the users and the following contributors:

- [Sebastian Rodríguez Colina]()
- Add your name here!

## License

Create ML App is open source software [licensed as MIT](./LICENSE)
