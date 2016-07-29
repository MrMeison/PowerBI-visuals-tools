[![Npm version](https://img.shields.io/npm/v/powerbi-visuals-tools.svg?style=flat)](https://www.npmjs.com/package/powerbi-visuals-tools)
[![Build Status](https://travis-ci.org/Microsoft/PowerBI-visuals-tools.svg?branch=master)](https://travis-ci.org/Microsoft/PowerBI-visuals-tools)
[![Build status](https://ci.appveyor.com/api/projects/status/ogws5ib33i35o5hs?svg=true)](https://ci.appveyor.com/project/spatney/powerbi-visuals-tools)

#PowerBI Visual Tools (pbiviz)

The easiest way to create custom visuals is by using the PowerBI command line tools which can be easily to installed via NPM. The command line tools provide everything you need to develop visuals and test them in live PowerBI reports and dashboards. 

**Features:**

* Visual project generation
* TypeScript compilation
* Less compilation
* Automatic live reload
* pbiviz packaging (for distribution)

##Basic Setup

Before you can get started you'll need to install the tools. This should only take a few seconds.

####Dependencies

Before you can run (or install) the command line tools you must install NodeJS.

* NodeJS 4.0+ Required (5.0 recommended) - [Download NodeJS](https://nodejs.org)

####Installation

To install the command line tools simply run the following command

```
npm install -g powerbi-visuals-tools
```

To confirm it was installed correctly you can run the command without any parameters which should display the help screen.

```
pbiviz
```

##Usage

Learn more about using these tools in the [Usage Guide](https://github.com/Microsoft/PowerBI-visuals-docs/tree/master/tools)

-------------

##Contributing

If you would like to contribute please see [How To Contribute](https://github.com/Microsoft/PowerBI-visuals-tools/blob/master/CONTRIBUTING.md).
