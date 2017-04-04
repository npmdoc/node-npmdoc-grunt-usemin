# api documentation for  [grunt-usemin (v3.1.1)](https://github.com/yeoman/grunt-usemin#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-usemin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-usemin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-usemin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-usemin)
#### Replaces references to non-optimized scripts or stylesheets into a set of HTML files (or any templates/views)

[![NPM](https://nodei.co/npm/grunt-usemin.png?downloads=true)](https://www.npmjs.com/package/grunt-usemin)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-usemin/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt-usemin_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-usemin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-usemin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-usemin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yeoman"
    },
    "bugs": {
        "url": "https://github.com/yeoman/grunt-usemin/issues"
    },
    "dependencies": {
        "chalk": "^1.1.1",
        "debug": "^2.1.3",
        "lodash": "^3.6.0",
        "path-exists": "^1.0.0"
    },
    "description": "Replaces references to non-optimized scripts or stylesheets into a set of HTML files (or any templates/views)",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "^0.11.1",
        "grunt-jscs": "^1.6.0",
        "grunt-mocha-cli": "^1.13.0",
        "mkdirp": "^0.5.0",
        "rimraf": "^2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "5ab679510d672cea566cc717abe8b8a009f641c2",
        "tarball": "https://registry.npmjs.org/grunt-usemin/-/grunt-usemin-3.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "lib",
        "tasks"
    ],
    "gitHead": "2057a27a4301ba0cf14fba3add2ce27a0a65de7c",
    "homepage": "https://github.com/yeoman/grunt-usemin#readme",
    "keywords": [
        "gruntplugin",
        "usemin",
        "yeoman",
        "html",
        "css",
        "optimize"
    ],
    "license": "BSD-2-Clause",
    "maintainers": [
        {
            "name": "sindresorhus",
            "email": "sindresorhus@gmail.com"
        },
        {
            "name": "paulirish",
            "email": "paul.irish@gmail.com"
        },
        {
            "name": "addyosmani",
            "email": "addyosmani@gmail.com"
        },
        {
            "name": "eddiemonge",
            "email": "eddie+npm@eddiemonge.com"
        },
        {
            "name": "passy",
            "email": "phartig@rdrei.net"
        },
        {
            "name": "sboudrias",
            "email": "admin@simonboudrias.com"
        },
        {
            "name": "arthurvr",
            "email": "contact@arthurverschaeve.be"
        }
    ],
    "name": "grunt-usemin",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yeoman/grunt-usemin.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "3.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt-usemin](#apidoc.module.grunt-usemin)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>configwriter (flow, dirs)](#apidoc.element.grunt-usemin.configwriter)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>fileprocessor (type, patterns, finder, logcb, blockReplacements)](#apidoc.element.grunt-usemin.fileprocessor)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>flow (flowConfig)](#apidoc.element.grunt-usemin.flow)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>revvedfinder (locator)](#apidoc.element.grunt-usemin.revvedfinder)
1.  object <span class="apidocSignatureSpan">grunt-usemin.</span>configwriter.prototype
1.  object <span class="apidocSignatureSpan">grunt-usemin.</span>fileprocessor.prototype
1.  object <span class="apidocSignatureSpan">grunt-usemin.</span>flow.prototype
1.  object <span class="apidocSignatureSpan">grunt-usemin.</span>revvedfinder.prototype

#### [module grunt-usemin.configwriter](#apidoc.module.grunt-usemin.configwriter)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>configwriter (flow, dirs)](#apidoc.element.grunt-usemin.configwriter.configwriter)

#### [module grunt-usemin.configwriter.prototype](#apidoc.module.grunt-usemin.configwriter.prototype)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>forEachStep (blockType, cb)](#apidoc.element.grunt-usemin.configwriter.prototype.forEachStep)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>postWriters (blockType)](#apidoc.element.grunt-usemin.configwriter.prototype.postWriters)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>process (file, config)](#apidoc.element.grunt-usemin.configwriter.prototype.process)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>stepWriters (blockType)](#apidoc.element.grunt-usemin.configwriter.prototype.stepWriters)

#### [module grunt-usemin.fileprocessor](#apidoc.module.grunt-usemin.fileprocessor)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>fileprocessor (type, patterns, finder, logcb, blockReplacements)](#apidoc.element.grunt-usemin.fileprocessor.fileprocessor)

#### [module grunt-usemin.fileprocessor.prototype](#apidoc.module.grunt-usemin.fileprocessor.prototype)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>process (filename, assetSearchPath)](#apidoc.element.grunt-usemin.fileprocessor.prototype.process)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>replaceBlocks (file)](#apidoc.element.grunt-usemin.fileprocessor.prototype.replaceBlocks)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>replaceWith (block)](#apidoc.element.grunt-usemin.fileprocessor.prototype.replaceWith)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>replaceWithRevved (lines, assetSearchPath)](#apidoc.element.grunt-usemin.fileprocessor.prototype.replaceWithRevved)

#### [module grunt-usemin.flow](#apidoc.module.grunt-usemin.flow)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>flow (flowConfig)](#apidoc.element.grunt-usemin.flow.flow)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.</span>formatStepName (step)](#apidoc.element.grunt-usemin.flow.formatStepName)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.</span>formatSteps (steps)](#apidoc.element.grunt-usemin.flow.formatSteps)

#### [module grunt-usemin.flow.prototype](#apidoc.module.grunt-usemin.flow.prototype)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>blockTypes ()](#apidoc.element.grunt-usemin.flow.prototype.blockTypes)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>post (blockType)](#apidoc.element.grunt-usemin.flow.prototype.post)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>setPost (post)](#apidoc.element.grunt-usemin.flow.prototype.setPost)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>setSteps (steps)](#apidoc.element.grunt-usemin.flow.prototype.setSteps)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>steps (blockType)](#apidoc.element.grunt-usemin.flow.prototype.steps)

#### [module grunt-usemin.revvedfinder](#apidoc.module.grunt-usemin.revvedfinder)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.</span>revvedfinder (locator)](#apidoc.element.grunt-usemin.revvedfinder.revvedfinder)

#### [module grunt-usemin.revvedfinder.prototype](#apidoc.module.grunt-usemin.revvedfinder.prototype)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>find (ofile, searchDirs)](#apidoc.element.grunt-usemin.revvedfinder.prototype.find)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>getCandidatesFromFS (file, searchPaths)](#apidoc.element.grunt-usemin.revvedfinder.prototype.getCandidatesFromFS)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>getCandidatesFromMapping (file, searchPaths)](#apidoc.element.grunt-usemin.revvedfinder.prototype.getCandidatesFromMapping)
1.  [function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>getRevvedCandidates (file, searchPaths)](#apidoc.element.grunt-usemin.revvedfinder.prototype.getRevvedCandidates)



# <a name="apidoc.module.grunt-usemin"></a>[module grunt-usemin](#apidoc.module.grunt-usemin)

#### <a name="apidoc.element.grunt-usemin.configwriter"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>configwriter (flow, dirs)](#apidoc.element.grunt-usemin.configwriter)
- description and source-code
```javascript
configwriter = function (flow, dirs) {
  var self = this;
  this.flow = flow;
  // FIXME: check dest and staging are furnished
  this.root = dirs.root;
  this.dest = dirs.dest;
  this.staging = dirs.staging;
  this.steps = {};
  this.postprocessors = [];
  this.destinations = {};

  // We need to create all the needed config writers, given them their output directory
  // E.g, if we do have the flow concat | uglify, the output dir will be .tmp/concat and dist
  // if the flow is concat | uglify | foo, the dirs will be .tmp/concat, .tmp/uglify, dist
  flow.blockTypes().forEach(function (blockType) {
    self.steps[blockType] = [];
    self.postprocessors[blockType] = [];

    flow.steps(blockType).forEach(function (item) {
      var step;
      if (_.isString(item)) {
        step = require(path.join(__dirname, 'config', item));
      } else {
        // Assume this is a user furnished step
        // FIXME: Add checks on object attributes
        step = item;
      }
      self.steps[blockType].push(step);
    });

    flow.post(blockType).forEach(function (item) {
      var pp;
      if (_.isString(item)) {
        pp = require(path.join(__dirname, 'config', item));
      } else {
        // Assume this is a user furnished post-processor
        // FIXME: Add checks on object attributes
        pp = item;
      }
      self.postprocessors[blockType].push(pp);
    });

  });

  // postprocessorsList.forEach(function (item) {
  //   var pp;
  //   if (_.isString(item)) {
  //     pp = require(path.join(__dirname, 'config', item));
  //   } else {
  //     // Assume this is a user furnished post-processor
  //     // FIXME: Add checks on object attributes
  //     pp = item;
  //   }
  //   self.postprocessors.push(pp);
  // });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt-usemin.fileprocessor"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>fileprocessor (type, patterns, finder, logcb, blockReplacements)](#apidoc.element.grunt-usemin.fileprocessor)
- description and source-code
```javascript
fileprocessor = function (type, patterns, finder, logcb, blockReplacements) {
  if (!type) {
    throw new Error('No type given');
  }

  if (!_.isArray(patterns)) {
    throw new Error('Patterns must be an array');
  }

  this.patterns = _defaultPatterns[type] || [];

  if (patterns.length) {
    this.patterns = this.patterns.concat(patterns);
  }

  this.log = logcb || function () {};

  if (!finder) {
    throw new Error('Missing parameter: finder');
  }
  this.finder = finder;


  this.blockReplacements = _.assign({}, defaultBlockReplacements);
  if (blockReplacements && _.keys(blockReplacements).length > 0) {
    _.assign(this.blockReplacements, blockReplacements);
  }

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt-usemin.flow"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>flow (flowConfig)](#apidoc.element.grunt-usemin.flow)
- description and source-code
```javascript
flow = function (flowConfig) {
  this.setSteps(flowConfig.steps);
  this.setPost(flowConfig.post);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt-usemin.revvedfinder"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>revvedfinder (locator)](#apidoc.element.grunt-usemin.revvedfinder)
- description and source-code
```javascript
revvedfinder = function (locator) {
  if (_.isFunction(locator)) {
    debug('using function locator');
    this.expandfn = locator;
  } else {
    debug('using file locator %s', locator);
    this.mapping = locator;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt-usemin.configwriter"></a>[module grunt-usemin.configwriter](#apidoc.module.grunt-usemin.configwriter)

#### <a name="apidoc.element.grunt-usemin.configwriter.configwriter"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>configwriter (flow, dirs)](#apidoc.element.grunt-usemin.configwriter.configwriter)
- description and source-code
```javascript
configwriter = function (flow, dirs) {
  var self = this;
  this.flow = flow;
  // FIXME: check dest and staging are furnished
  this.root = dirs.root;
  this.dest = dirs.dest;
  this.staging = dirs.staging;
  this.steps = {};
  this.postprocessors = [];
  this.destinations = {};

  // We need to create all the needed config writers, given them their output directory
  // E.g, if we do have the flow concat | uglify, the output dir will be .tmp/concat and dist
  // if the flow is concat | uglify | foo, the dirs will be .tmp/concat, .tmp/uglify, dist
  flow.blockTypes().forEach(function (blockType) {
    self.steps[blockType] = [];
    self.postprocessors[blockType] = [];

    flow.steps(blockType).forEach(function (item) {
      var step;
      if (_.isString(item)) {
        step = require(path.join(__dirname, 'config', item));
      } else {
        // Assume this is a user furnished step
        // FIXME: Add checks on object attributes
        step = item;
      }
      self.steps[blockType].push(step);
    });

    flow.post(blockType).forEach(function (item) {
      var pp;
      if (_.isString(item)) {
        pp = require(path.join(__dirname, 'config', item));
      } else {
        // Assume this is a user furnished post-processor
        // FIXME: Add checks on object attributes
        pp = item;
      }
      self.postprocessors[blockType].push(pp);
    });

  });

  // postprocessorsList.forEach(function (item) {
  //   var pp;
  //   if (_.isString(item)) {
  //     pp = require(path.join(__dirname, 'config', item));
  //   } else {
  //     // Assume this is a user furnished post-processor
  //     // FIXME: Add checks on object attributes
  //     pp = item;
  //   }
  //   self.postprocessors.push(pp);
  // });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt-usemin.configwriter.prototype"></a>[module grunt-usemin.configwriter.prototype](#apidoc.module.grunt-usemin.configwriter.prototype)

#### <a name="apidoc.element.grunt-usemin.configwriter.prototype.forEachStep"></a>[function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>forEachStep (blockType, cb)](#apidoc.element.grunt-usemin.configwriter.prototype.forEachStep)
- description and source-code
```javascript
forEachStep = function (blockType, cb) {
  var writersCount = this.stepWriters(blockType).length;
  this.stepWriters(blockType).forEach(function (step, index) {
    cb(step, index === writersCount - 1);
  });
}
```
- example usage
```shell
...
    };

    if (block.searchPath.length > 0) {
// FIXME: we must use all the furnished directories
context.inDir = block.searchPath[0];
    }

    self.forEachStep(block.type, function (writer, last) {
var blockConfig;
var fileSet;
var dest;

// If this is the last writer of the pipe, we need to output
// in the destination directory
context.outDir = last ? self.dest : path.join(self.staging, writer.name);
...
```

#### <a name="apidoc.element.grunt-usemin.configwriter.prototype.postWriters"></a>[function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>postWriters (blockType)](#apidoc.element.grunt-usemin.configwriter.prototype.postWriters)
- description and source-code
```javascript
postWriters = function (blockType) {
  return this.postprocessors[blockType] || [];
}
```
- example usage
```shell
...
  staging: staging
});

var cfgNames = [];
c.stepWriters().forEach(function (i) {
  cfgNames.push(i.name);
});
c.postWriters().forEach(function (i) {
  cfgNames.push(i.name);
});
var gruntConfig = {};
_.forEach(cfgNames, function (name) {
  gruntConfig[name] = grunt.config(name) || {};
});
...
```

#### <a name="apidoc.element.grunt-usemin.configwriter.prototype.process"></a>[function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>process (file, config)](#apidoc.element.grunt-usemin.configwriter.prototype.process)
- description and source-code
```javascript
process = function (file, config) {
  var self = this;
  var lfile = file;

  config = config || {};

  if (_.isString(file)) {
    lfile = new File(file);
  }

  lfile.blocks.forEach(function (block) {
    // FIXME: support several searchPath...
    var context = {
      inDir: self.root || lfile.searchPath[0],
      inFiles: block.src,
      outFiles: []
    };

    if (block.searchPath.length > 0) {
      // FIXME: we must use all the furnished directories
      context.inDir = block.searchPath[0];
    }

    self.forEachStep(block.type, function (writer, last) {
      var blockConfig;
      var fileSet;
      var dest;

      // If this is the last writer of the pipe, we need to output
      // in the destination directory
      context.outDir = last ? self.dest : path.join(self.staging, writer.name);
      context.last = last;
      config[writer.name] = config[writer.name] || {};
      config[writer.name].generated = config[writer.name].generated || {};
      context.options = config[writer.name];
      // config[writer.name].generated = _.extend(config[writer.name].generated, writer.createConfig(context, block));
      blockConfig = writer.createConfig(context, block);
      if (blockConfig.files) {
        fileSet = blockConfig.files;
        blockConfig.files = [];
        fileSet.forEach(function (filesInfo) {
          dest = filesInfo.dest;
          if (!self.destinations[dest]) {
            self.destinations[dest] = filesInfo;
            blockConfig.files.push(filesInfo);
          } else if (!_.isEqual(self.destinations[dest], filesInfo)) {
            throw new Error('Different sources attempting to write to the same destination:\n ' + JSON.stringify(self.destinations
[dest], null, '    ') + '\n  ' + JSON.stringify(blockConfig, null, '    '));
          }
        });

        if (blockConfig.files.length) {
          config[writer.name].generated = deepMerge(config[writer.name].generated, blockConfig);
        }
      } else {
        config[writer.name].generated = deepMerge(config[writer.name].generated, blockConfig);
      }
      context.inDir = context.outDir;
      context.inFiles = context.outFiles;
      context.outFiles = [];
      context.options = null;
    });

    context.inDir = lfile.searchPath[0];
    if (block.searchPath.length > 0) {
      context.inDir = block.searchPath[0];
    }
    context.inFiles = block.src;

    if (self.postprocessors.hasOwnProperty(block.type)) {
      self.postprocessors[block.type].forEach(function (pp) {
        config[pp.name] = config[pp.name] || {};
        context.options = config[pp.name];
        config[pp.name] = _.extend(config[pp.name], pp.createConfig(context, block));
        context.options = null;
      });
    }
  });

  return config;
}
```
- example usage
```shell
...
}, fileObj.src);
files.forEach(function (filename) {
  debug('looking at file %s', filename);

  grunt.verbose.writeln(chalk.bold('Processing as ' + options.type.toUpperCase() + ' - ') + chalk.cyan(filename));

  // Our revved version locator
  var content = handler.process(filename, options.assetsDirs);

  // write the new content to disk
  grunt.file.write(filename, content);

});

grunt.log.writeln('Replaced ' + chalk.cyan(files.length) + ' ' +
...
```

#### <a name="apidoc.element.grunt-usemin.configwriter.prototype.stepWriters"></a>[function <span class="apidocSignatureSpan">grunt-usemin.configwriter.prototype.</span>stepWriters (blockType)](#apidoc.element.grunt-usemin.configwriter.prototype.stepWriters)
- description and source-code
```javascript
stepWriters = function (blockType) {
  var writers;

  if (blockType) {
    writers = this.steps[blockType] || [];
  } else {
    writers = _.uniq(_.flatten(_.values(this.steps), true)); // Only 1 level
  }
  return writers;
}
```
- example usage
```shell
...
//
// Iterate over steps for the furnished block type.
// The callback is called with the following parameters:
//  - step : the step by itself
//  - last : boolean indicating if this is the last writer of the pipe
//
ConfigWriter.prototype.forEachStep = function (blockType, cb) {
  var writersCount = this.stepWriters(blockType).length;
  this.stepWriters(blockType).forEach(function (step, index) {
    cb(step, index === writersCount - 1);
  });
};

//
// Process the blocks of the furnished file. This means:
...
```



# <a name="apidoc.module.grunt-usemin.fileprocessor"></a>[module grunt-usemin.fileprocessor](#apidoc.module.grunt-usemin.fileprocessor)

#### <a name="apidoc.element.grunt-usemin.fileprocessor.fileprocessor"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>fileprocessor (type, patterns, finder, logcb, blockReplacements)](#apidoc.element.grunt-usemin.fileprocessor.fileprocessor)
- description and source-code
```javascript
fileprocessor = function (type, patterns, finder, logcb, blockReplacements) {
  if (!type) {
    throw new Error('No type given');
  }

  if (!_.isArray(patterns)) {
    throw new Error('Patterns must be an array');
  }

  this.patterns = _defaultPatterns[type] || [];

  if (patterns.length) {
    this.patterns = this.patterns.concat(patterns);
  }

  this.log = logcb || function () {};

  if (!finder) {
    throw new Error('Missing parameter: finder');
  }
  this.finder = finder;


  this.blockReplacements = _.assign({}, defaultBlockReplacements);
  if (blockReplacements && _.keys(blockReplacements).length > 0) {
    _.assign(this.blockReplacements, blockReplacements);
  }

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt-usemin.fileprocessor.prototype"></a>[module grunt-usemin.fileprocessor.prototype](#apidoc.module.grunt-usemin.fileprocessor.prototype)

#### <a name="apidoc.element.grunt-usemin.fileprocessor.prototype.process"></a>[function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>process (filename, assetSearchPath)](#apidoc.element.grunt-usemin.fileprocessor.prototype.process)
- description and source-code
```javascript
process = function (filename, assetSearchPath) {
  debug('processing file %s', filename, assetSearchPath);

  if (_.isString(filename)) {
    this.file = new File(filename);
  } else {
    // filename is an object and should conform to lib/file.js API
    this.file = filename;
  }

  if (assetSearchPath && assetSearchPath.length !== 0) {
    this.file.searchPath = assetSearchPath;
  }

  var content = this.replaceWithRevved(this.replaceBlocks(this.file), this.file.searchPath);

  return content;
}
```
- example usage
```shell
...
}, fileObj.src);
files.forEach(function (filename) {
  debug('looking at file %s', filename);

  grunt.verbose.writeln(chalk.bold('Processing as ' + options.type.toUpperCase() + ' - ') + chalk.cyan(filename));

  // Our revved version locator
  var content = handler.process(filename, options.assetsDirs);

  // write the new content to disk
  grunt.file.write(filename, content);

});

grunt.log.writeln('Replaced ' + chalk.cyan(files.length) + ' ' +
...
```

#### <a name="apidoc.element.grunt-usemin.fileprocessor.prototype.replaceBlocks"></a>[function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>replaceBlocks (file)](#apidoc.element.grunt-usemin.fileprocessor.prototype.replaceBlocks)
- description and source-code
```javascript
function replaceBlocks(file) {
  var result = file.content;
  var linefeed = /\r\n/g.test(result) ? '\r\n' : '\n';
  file.blocks.forEach(function (block) {
    var blockLine = block.raw.join(linefeed);
    result = result.replace(blockLine, this.replaceWith(block));
  }, this);
  return result;
}
```
- example usage
```shell
...
    this.file = filename;
  }

  if (assetSearchPath && assetSearchPath.length !== 0) {
    this.file.searchPath = assetSearchPath;
  }

  var content = this.replaceWithRevved(this.replaceBlocks(this.file), this.file.searchPath);

  return content;
};
...
```

#### <a name="apidoc.element.grunt-usemin.fileprocessor.prototype.replaceWith"></a>[function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>replaceWith (block)](#apidoc.element.grunt-usemin.fileprocessor.prototype.replaceWith)
- description and source-code
```javascript
function replaceWith(block) {
  var result;
  var conditionalStart = block.conditionalStart ? block.conditionalStart + '\n' + block.indent : '';
  var conditionalEnd = block.conditionalEnd ? '\n' + block.indent + block.conditionalEnd : '';
  if (typeof block.src === 'undefined' || block.src === null || block.src.length === 0) {
    // there are no css or js files in the block, remove it completely
    result = '';
  } else if (_.contains(_.keys(this.blockReplacements), block.type)) {
    result = block.indent + conditionalStart + this.blockReplacements[block.type](block) + conditionalEnd;
  } else {
    result = '';
  }
  return result;
}
```
- example usage
```shell
...
// Replace blocks by their target
//
FileProcessor.prototype.replaceBlocks = function replaceBlocks(file) {
var result = file.content;
var linefeed = /\r\n/g.test(result) ? '\r\n' : '\n';
file.blocks.forEach(function (block) {
  var blockLine = block.raw.join(linefeed);
  result = result.replace(blockLine, this.replaceWith(block));
}, this);
return result;
};


FileProcessor.prototype.replaceWith = function replaceWith(block) {
var result;
...
```

#### <a name="apidoc.element.grunt-usemin.fileprocessor.prototype.replaceWithRevved"></a>[function <span class="apidocSignatureSpan">grunt-usemin.fileprocessor.prototype.</span>replaceWithRevved (lines, assetSearchPath)](#apidoc.element.grunt-usemin.fileprocessor.prototype.replaceWithRevved)
- description and source-code
```javascript
function replaceWithRevved(lines, assetSearchPath) {
  // Replace script sources
  var self = this;
  var content = lines;
  var regexps = this.patterns;
  var identity = function (m) {
    return m;
  };

  // Replace reference to script with the actual name of the revved script
  regexps.forEach(function (rxl) {
    var filterIn = rxl[2] || identity;
    var filterOut = rxl[3] || identity;

    self.log(rxl[1]);
    content = content.replace(rxl[0], function (match, src) {
      // Consider reference from site root
      var srcFile = filterIn(src);

      debug('Let\'s replace ' + src);

      debug('Looking for revved version of ' + srcFile + ' in ', assetSearchPath);

      var file = self.finder.find(srcFile, assetSearchPath);

      debug('Found file \'%s\'', file);

      if (src === '/') {
        return match;
      }

      var res = match.replace(src, filterOut(file));
      if (srcFile !== file) {
        self.log(chalk.cyan(src) + ' changed to ' + chalk.cyan(file));
      }
      return res;
    });
  });

  return content;
}
```
- example usage
```shell
...
    this.file = filename;
  }

  if (assetSearchPath && assetSearchPath.length !== 0) {
    this.file.searchPath = assetSearchPath;
  }

  var content = this.replaceWithRevved(this.replaceBlocks(this.file), this.file.searchPath);

  return content;
};
...
```



# <a name="apidoc.module.grunt-usemin.flow"></a>[module grunt-usemin.flow](#apidoc.module.grunt-usemin.flow)

#### <a name="apidoc.element.grunt-usemin.flow.flow"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>flow (flowConfig)](#apidoc.element.grunt-usemin.flow.flow)
- description and source-code
```javascript
flow = function (flowConfig) {
  this.setSteps(flowConfig.steps);
  this.setPost(flowConfig.post);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt-usemin.flow.formatStepName"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.</span>formatStepName (step)](#apidoc.element.grunt-usemin.flow.formatStepName)
- description and source-code
```javascript
formatStepName = function (step) {
  if (typeof step === 'string') {
    return /uglify/.test(step) ? 'uglify' : step;
  }

  step.name = /uglify/.test(step.name) ? 'uglify' : step.name;

  return step;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.grunt-usemin.flow.formatSteps"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.</span>formatSteps (steps)](#apidoc.element.grunt-usemin.flow.formatSteps)
- description and source-code
```javascript
formatSteps = function (steps) {
  var formattedSteps = {};
  _.forIn(steps, function (config, type) {
    formattedSteps[type] = config.map(Flow.formatStepName);
  });

  return formattedSteps;
}
```
- example usage
```shell
...
return this._steps[blockType] || [];
};

//
// Set the steps for the flow
//
Flow.prototype.setSteps = function (steps) {
this._steps = Flow.formatSteps(steps) || {};
};

//
// Returns the postprocessors for the furnished block type
//
Flow.prototype.post = function (blockType) {
return this._post[blockType] || [];
...
```



# <a name="apidoc.module.grunt-usemin.flow.prototype"></a>[module grunt-usemin.flow.prototype](#apidoc.module.grunt-usemin.flow.prototype)

#### <a name="apidoc.element.grunt-usemin.flow.prototype.blockTypes"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>blockTypes ()](#apidoc.element.grunt-usemin.flow.prototype.blockTypes)
- description and source-code
```javascript
blockTypes = function () {
  return _.union(_.keys(this._steps), _.keys(this._post));
}
```
- example usage
```shell
...
  this.steps = {};
  this.postprocessors = [];
  this.destinations = {};

  // We need to create all the needed config writers, given them their output directory
  // E.g, if we do have the flow concat | uglify, the output dir will be .tmp/concat and dist
  // if the flow is concat | uglify | foo, the dirs will be .tmp/concat, .tmp/uglify, dist
  flow.blockTypes().forEach(function (blockType) {
self.steps[blockType] = [];
self.postprocessors[blockType] = [];

flow.steps(blockType).forEach(function (item) {
  var step;
  if (_.isString(item)) {
    step = require(path.join(__dirname, 'config', item));
...
```

#### <a name="apidoc.element.grunt-usemin.flow.prototype.post"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>post (blockType)](#apidoc.element.grunt-usemin.flow.prototype.post)
- description and source-code
```javascript
post = function (blockType) {
  return this._post[blockType] || [];
}
```
- example usage
```shell
...
    // Assume this is a user furnished step
    // FIXME: Add checks on object attributes
    step = item;
  }
  self.steps[blockType].push(step);
});

flow.post(blockType).forEach(function (item) {
  var pp;
  if (_.isString(item)) {
    pp = require(path.join(__dirname, 'config', item));
  } else {
    // Assume this is a user furnished post-processor
    // FIXME: Add checks on object attributes
    pp = item;
...
```

#### <a name="apidoc.element.grunt-usemin.flow.prototype.setPost"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>setPost (post)](#apidoc.element.grunt-usemin.flow.prototype.setPost)
- description and source-code
```javascript
setPost = function (post) {
  this._post = Flow.formatSteps(post) || {};
}
```
- example usage
```shell
...
//      js: ['bar', 'baz'],
//      css: ['foo']
//     }
//   }
//
var Flow = module.exports = function (flowConfig) {
this.setSteps(flowConfig.steps);
this.setPost(flowConfig.post);
};

Flow.formatStepName = function (step) {
if (typeof step === 'string') {
  return /uglify/.test(step) ? 'uglify' : step;
}
...
```

#### <a name="apidoc.element.grunt-usemin.flow.prototype.setSteps"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>setSteps (steps)](#apidoc.element.grunt-usemin.flow.prototype.setSteps)
- description and source-code
```javascript
setSteps = function (steps) {
  this._steps = Flow.formatSteps(steps) || {};
}
```
- example usage
```shell
...
//    steps: {
//      js: ['bar', 'baz'],
//      css: ['foo']
//     }
//   }
//
var Flow = module.exports = function (flowConfig) {
this.setSteps(flowConfig.steps);
this.setPost(flowConfig.post);
};

Flow.formatStepName = function (step) {
if (typeof step === 'string') {
  return /uglify/.test(step) ? 'uglify' : step;
}
...
```

#### <a name="apidoc.element.grunt-usemin.flow.prototype.steps"></a>[function <span class="apidocSignatureSpan">grunt-usemin.flow.prototype.</span>steps (blockType)](#apidoc.element.grunt-usemin.flow.prototype.steps)
- description and source-code
```javascript
steps = function (blockType) {
  return this._steps[blockType] || [];
}
```
- example usage
```shell
...
  // We need to create all the needed config writers, given them their output directory
  // E.g, if we do have the flow concat | uglify, the output dir will be .tmp/concat and dist
  // if the flow is concat | uglify | foo, the dirs will be .tmp/concat, .tmp/uglify, dist
  flow.blockTypes().forEach(function (blockType) {
self.steps[blockType] = [];
self.postprocessors[blockType] = [];

flow.steps(blockType).forEach(function (item) {
  var step;
  if (_.isString(item)) {
    step = require(path.join(__dirname, 'config', item));
  } else {
    // Assume this is a user furnished step
    // FIXME: Add checks on object attributes
    step = item;
...
```



# <a name="apidoc.module.grunt-usemin.revvedfinder"></a>[module grunt-usemin.revvedfinder](#apidoc.module.grunt-usemin.revvedfinder)

#### <a name="apidoc.element.grunt-usemin.revvedfinder.revvedfinder"></a>[function <span class="apidocSignatureSpan">grunt-usemin.</span>revvedfinder (locator)](#apidoc.element.grunt-usemin.revvedfinder.revvedfinder)
- description and source-code
```javascript
revvedfinder = function (locator) {
  if (_.isFunction(locator)) {
    debug('using function locator');
    this.expandfn = locator;
  } else {
    debug('using file locator %s', locator);
    this.mapping = locator;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.grunt-usemin.revvedfinder.prototype"></a>[module grunt-usemin.revvedfinder.prototype](#apidoc.module.grunt-usemin.revvedfinder.prototype)

#### <a name="apidoc.element.grunt-usemin.revvedfinder.prototype.find"></a>[function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>find (ofile, searchDirs)](#apidoc.element.grunt-usemin.revvedfinder.prototype.find)
- description and source-code
```javascript
function find(ofile, searchDirs) {
  var file = ofile;
  var searchPaths = searchDirs;
  var absolute;
  var prefix;

  if (_.isString(searchDirs)) {
    searchPaths = [searchDirs];
  }

  debug('Looking for revved version of %s in ', ofile, searchPaths);

  // do not touch external files or the root
  // FIXME: Should get only relative files
  if (ofile.match(/:\/\//) || ofile === '') {
    return ofile;
  }

  if (file[0] === '/') {
    // We need to remember this is an absolute file, but transform it
    // to a relative one
    absolute = true;
    file = file.replace(/^(\/+)/, function (match, header) {
      prefix = header;
      return '';
    });
  }

  var filepaths = this.getRevvedCandidates(file, searchPaths);

  var filepath = filepaths[0];
  debug('filepath is now ', filepath);

  // not a file in temp, skip it
  if (!filepath) {
    return ofile;
  }

  // var filename = path.basename(filepath);
  // handle the relative prefix (with always unix like path even on win32)
  // if (dirname !== '.') {
  //   filename = [dirname, filename].join('/');
  // }

  if (absolute) {
    filepath = prefix + filepath;
  }

  debug('Let\'s return %s', filepath);
  return filepath;
}
```
- example usage
```shell
...
// Consider reference from site root
var srcFile = filterIn(src);

debug('Let\'s replace ' + src);

debug('Looking for revved version of ' + srcFile + ' in ', assetSearchPath);

var file = self.finder.find(srcFile, assetSearchPath);

debug('Found file \'%s\'', file);

if (src === '/') {
  return match;
}
...
```

#### <a name="apidoc.element.grunt-usemin.revvedfinder.prototype.getCandidatesFromFS"></a>[function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>getCandidatesFromFS (file, searchPaths)](#apidoc.element.grunt-usemin.revvedfinder.prototype.getCandidatesFromFS)
- description and source-code
```javascript
getCandidatesFromFS = function (file, searchPaths) {
  var extname = path.extname(file);
  var basename = path.basename(file, extname);
  var dirname = path.dirname(file);
  var hex = '[0-9a-fA-F]+';
  var regPrefix = '(' + hex + '\\.' + regexpQuote(basename) + ')';
  var regSuffix = '(' + regexpQuote(basename) + '\\.' + hex + regexpQuote(extname) + ')';
  var revvedRx = new RegExp(regPrefix + '|' + regSuffix);
  var candidates = [];
  var self = this;

  searchPaths.forEach(function (sp) {
    var searchString = path.join(sp, dirname, basename + '.*' + extname);
    var prefixSearchString = path.join(sp, dirname, '*.' + basename + extname);

    if (searchString.indexOf('#') === 0) {
      // patterns starting with # are treated as comments by the glob implementation which returns undefined,
      // which would cause an unhandled exception in self.expandfn below so the file is never written
      return;
    }

    debug('Looking for %s and %s on disk', searchString, prefixSearchString);

    var files = self.expandfn([searchString, prefixSearchString]);

    debug('Found ', files);

    // Keep only files that look like a revved file
    var goodFiles = files.filter(function (f) {
      return f.match(revvedRx);
    });

    // We must now remove the search path from the beginning, and add them to the
    // list of candidates
    goodFiles.forEach(function (gf) {
      var goodFileName = path.basename(gf);
      if (!file.match(/\//)) {
        // We only get a file (i.e. no dirs), so let's send back
        // what we found
        debug('Adding %s to candidates', goodFileName);
        candidates.push(goodFileName);
      } else {
        debug('Adding %s / %s to candidates', dirname, goodFileName);
        candidates.push(dirname + '/' + goodFileName);
      }
    });
  });

  return candidates;
}
```
- example usage
```shell
...
  // FIXME:

  if (this.mapping) {
    debug('Looking at mapping');
    candidates = this.getCandidatesFromMapping(file, searchPaths);
  } else {
    debug('Looking on disk');
    candidates = this.getCandidatesFromFS(file, searchPaths);
  }

  return candidates;
};

//
// Find a revved version of +ofile+ (i.e. a file which name is ending with +ofile+), relatively
...
```

#### <a name="apidoc.element.grunt-usemin.revvedfinder.prototype.getCandidatesFromMapping"></a>[function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>getCandidatesFromMapping (file, searchPaths)](#apidoc.element.grunt-usemin.revvedfinder.prototype.getCandidatesFromMapping)
- description and source-code
```javascript
getCandidatesFromMapping = function (file, searchPaths) {
  var dirname = path.dirname(file);
  var filepath = dirname === '.' ? '' : dirname + '/';
  var candidates = [];
  var self = this;

  searchPaths.forEach(function (sp) {
    var key = path.normalize(path.join(sp, file));
    debug('Looking at mapping for %s (from %s/%s)', key, sp, file);

    if (self.mapping[key]) {
      // We need to transform the actual file to a form that matches the one we received
      // For example if we received file 'foo/images/test.png' with searchPaths == ['dist'],
      // and found in mapping that 'dist/foo/images/test.png' has been renamed
      // 'dist/foo/images/test.1234.png' by grunt-rev, then we need to return
      // 'foo/images/test.1234.png'
      var cfile = path.basename(self.mapping[key]);
      candidates.push(filepath + cfile);
      debug('Found a candidate: %s/%s', dirname, cfile);
    }
  });

  return candidates;
}
```
- example usage
```shell
...
  // Our strategy depends on what we get at creation time: either a mapping, and we "just"
  // need to do look-up in the mapping, or an expand function and we need to find relevant files
  // on the disk
  // FIXME:

  if (this.mapping) {
    debug('Looking at mapping');
    candidates = this.getCandidatesFromMapping(file, searchPaths);
  } else {
    debug('Looking on disk');
    candidates = this.getCandidatesFromFS(file, searchPaths);
  }

  return candidates;
};
...
```

#### <a name="apidoc.element.grunt-usemin.revvedfinder.prototype.getRevvedCandidates"></a>[function <span class="apidocSignatureSpan">grunt-usemin.revvedfinder.prototype.</span>getRevvedCandidates (file, searchPaths)](#apidoc.element.grunt-usemin.revvedfinder.prototype.getRevvedCandidates)
- description and source-code
```javascript
getRevvedCandidates = function (file, searchPaths) {
  var candidates;

  // Our strategy depends on what we get at creation time: either a mapping, and we "just"
  // need to do look-up in the mapping, or an expand function and we need to find relevant files
  // on the disk
  // FIXME:

  if (this.mapping) {
    debug('Looking at mapping');
    candidates = this.getCandidatesFromMapping(file, searchPaths);
  } else {
    debug('Looking on disk');
    candidates = this.getCandidatesFromFS(file, searchPaths);
  }

  return candidates;
}
```
- example usage
```shell
...
  absolute = true;
  file = file.replace(/^(\/+)/, function (match, header) {
    prefix = header;
    return '';
  });
}

var filepaths = this.getRevvedCandidates(file, searchPaths);

var filepath = filepaths[0];
debug('filepath is now ', filepath);

// not a file in temp, skip it
if (!filepath) {
  return ofile;
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
