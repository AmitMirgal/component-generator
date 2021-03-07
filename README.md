# component-generator

CLI to generate files based on your project

## To install

```bash
git clone https://github.com/AmitMirgal/component-generator.git
cd component-generator

npm install

# if you want the CLI to available anywhere
# the parent directory has a reference of the current directory in this case the current project directory i.e. component-generator
npm link .

```

## Usage

```bash
# from the repo
npm run generator

# if you have installed globally
generator

# to pre-fill first prompt
generator MyAwesomeButton

```

## Motivation and Context

I've inspired from the bala's blog and realize that it's a good idea to automate the templates. He has explained in details in his blog.

[Balavishnuvj Blog](https://balavishnuvj.com/blog/building-your-own-component-generator/)
