```{include} _templates/nav.html

```

# Framework

Now that we have our `git` repository created, we’re going to start installing the tools we need to start building a page.

```{contents} Sections
  :depth: 1
  :local:
```

## What is a framework?

The first and more important is our [framework](https://en.wikipedia.org/wiki/Software_framework).

What's that? Nothing more than fancy name for a set of software tools that, working together, can stand up a website.

It takes dozens of different software tricks to pull a good site together. Frameworks aim to make the challenge easier by organizing a curated set of tools into a simplified system that saves time.

There are a lot of different frameworks out there. Maybe you've heard of some them, like [Django](https://www.djangoproject.com/) for Python, [Rails](http://rubyonrails.org) for Ruby or [React](https://reactjs.org/) for Node.js.

While some frameworks are more popular than others, each newsroom tends to go its own way with its custom system for publishing pages. The programming languages and the details vary, but the fundamentals are almost all the same.

```{note}
Some of them have even been released as open-source software. They include:

- Reuters’ [bluprint](https://github.com/reuters-graphics/bluprint_graphics-kit)
- The Texas Tribune’s [data-visuals-create](https://github.com/texastribune/data-visuals-create)
- The Seattle Times' [newsapp-template](https://github.com/seattletimes/newsapp-template/)
- The NPR Apps team's [dailygraphics](https://github.com/nprapps/dailygraphics)
- Politico's [generator-politico-graphics](https://github.com/The-Politico/generator-politico-graphics)
```

The GitHub template we cloned in the last chapter is a demonstration of the Los Angeles Times tool, which is known as [baker](https://github.com/datadesk/baker) and published as free and open software that anyone can easily reuse at [github.com/datadesk/baker-example-page-template](https://github.com/datadesk/baker-example-page-template).

The remainder of this tutorial will demonstrate how to use The Times tool to publish a page to the web.

While many of the particulars are specific to the choices made but Times developers, most of the overall principles are shared by the frameworks employed at other newsrooms.

## Install our system

The Times’ baker framework — like most of its peers’ — is developed using the Node.js JavaScript programming language.

Now that you have the fundamentals cloned to your computer, installing the underlying dependencies necessary to develop a page requires that you use Node.js’s package manager `npm`.

From your terminal positioned inside of the repository’s directory, run the following to get everything necessary to start work:

```bash
npm install
```

## Start the test server

Once the dependencies have been installed, you’re ready to preview the project. Run the following to start the test server:

```bash
npm start
```

Visit [localhost:3000](http://localhost:3000) in your browser. There you can see the generic website offered as a starting point by our framework.

![npm start](_static/npm-start.png)

Congratulations, you've got your framework up and running. Now we're ready to start developing our own content.
