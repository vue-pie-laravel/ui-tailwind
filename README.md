# Tailwind CSS UI

> You can use this respoitory to help you configure tailwind for your own project reguardless of what backend framework you work with.
> This config is compatible with a [Vue CLI](https://cli.vuejs.org/) setup, see **Independant Usage** below in this readme doc.
>
> Otherwise if you are utilizing the full Lara CLI guide then please ensure you have first followed the instructions from the [Core Repository](https://github.com/laracli/core) before you continue below.


# Installation

[Download](https://github.com/laracli/ui-tailwind/archive/master.zip) and upack this UI source into the root of your Laravel project, some files will be overwritten such as `package.json`.

Then using a terminal window in the root of your project run `yarn install`.

Finally in a terminal window from any location run `vue ui` to launch the [CLI Service](https://cli.vuejs.org/guide/cli-service.html#cli-service) and use the web interface to import your new project, then run `serve` from the tool.

You are all done, write some code!

# Independant Usage

If you just want to know how to tconfigure TailwindCSS for your own project, the files of interest to you are:

| Files | Hint |
| - | - |
| package.json | **Line** Post CSS Plugin entry; find `"tailwindcss"` |
| tailwind.config.js | **File** |
| src/scss/\_tailwind.scss | **File** |

That is all, you can use Tailwind!
