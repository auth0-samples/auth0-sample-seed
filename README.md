# Overview

This is the seed project which can be used for sample projects.

All examples must contain a `metadata.json` file which describes the sample project. Here is an example of the `metadata.json` file:

```
{
    "title": "This is a sample title",
    "description": "This is a long description for the sample",
    "seed": "true",
    "languages":[
        "csharp"
    ],
    "frameworks":[
        "aspnet",
        "aspnetwebapi"
    ],
    "tags": [
        "lock",
        "google",
        "oauth"
    ]
}
```

The fields are as follows:

* `title`: A short title for the sample. Try to be as short and descriptive as possible.
* `description`: A longer description which describes the purpose of the sample, as well as what the user can expect to learn from the sample. This will typically be around a paragraph long.
* `seed`: Specifies whether this is a seed project. `true` if it is, otherwise `false`. If it is not a seed project (i.e. `false`), the attribute can also be omitted completely from the metadata file.
* `languages`: The programming languages used in this sample. This is an array of values. Typically a sample will be implemented in only one programming language, but for some samples we may find that it is implemented in multiple languages. See below for a list of possible values.
* `frameworks`: The frameworks used in this sample. Can be one or more. See below for a list of possible values.
* `tags`: Any keywords you feel makes sense which relates to this sample. This will be indexed by the search engine, so it is a good place to add keywords you think the user will search on.

## Taxonomies

This desribes the possible values for the taxonomies. In particular the `languages` and `frameworks`.

### Languages

* csharp
* java
* javascript
* typescript
* php
* python
* ruby
* objectivec
* swift
* go

### Frameworks

* aspnet
* aspnetmvc
* aspnetcore
* aspnetwebapi
* asp
* wcf
* meteor
* nancyfx
* laravel
* symfony
* rails
* servicestack
* cordova
* electron
* ionic
* phonegap
* react-native
* uwp
* winphone
* wpf
* winforms
* xamarin
* xamarin-forms
* angularjs
* aurelia
* emberjs
* jquery
* react
* socketio
* vuejs
* express
* passportjs
* nodejs
* spring

