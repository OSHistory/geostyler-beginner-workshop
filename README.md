# geostyler-beginner-workshop
Workshop on how to use GeoStyler from scratch

The online workshop can be found on [https://geostyler.github.io/geostyler-beginner-workshop/](https://geostyler.github.io/geostyler-beginner-workshop/).

## Local Build

The workshop is generated with [Docosaurus](https://docusaurus.io/). To build locally 
change into the `workshop` directory. 

Install the dependencies with `npm install` and run `npm run start` to start 
the development server with will run a [Local Server](http://localhost:3000). Use `npm run build` to build the static site.

## Hints 

Refer to [Docusaurus Quick Tour]() or the extensive [documentation](https://docusaurus.io/docs). 

Here are some hints to get you started in this repository. 

All pages are found in `docs` subfolder. Each subdirectory creates a new TOC-level.
The order of the files is set in `sidebar.js`. The route is redirected to the `docs` folder
by setting `routeBasePath: '/',routeBasePath: '/'` 
in `workshop-docusaurus/docusaurus.config.js`.


## <a name="license"></a>License

This workshop is released under the BSD 2-Clause license. Please see the file
[`LICENSE`](https://github.com/geostyler/geostyler-beginner-workshop/blob/master/LICENSE) in the
root of this repository.

The compiled workshop is released under a [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en) license. 
