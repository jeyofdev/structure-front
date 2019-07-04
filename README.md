# structure-front

Basic structure for the default CSS style of a project without CSS framework




### Tools

Check that the latest version of [Nodejs](https://nodejs.org/en/download/) is installed :
```sh
$ node -v
```

Check that the latest version of [Yarn](https://yarnpkg.com/en/docs/install) is installed :
```sh
$ yarn -v
```



### Webpack installation

Install webpack from CLI
```sh
$ yarn add webpack --dev
```



### Available Webpack commands

* `yarn run dev` — Compile assets for developing when file changes are made
* `yarn run prod` — Compile and optimize the files in assets directory for production




### Initialize a project

Clone the depot and install all the dependencies :
```sh
$ yarn install
```




### Grid system

Container :
```sh
  <div class="container">...</div>
  <div class="container-fluid">...</div>
```

Container + row :
```sh
  <div class="container">
    <div class="row">...</div>
  </div>
```

column :
```sh
  <div class="container">
    <div class="row">
      <div class="col-6 col-md-4 col-lg-4 col-xs-4">...</div>
      <div class="col-6 col-md-4 col-lg-4 col-xs-4">...</div>
      <div class="col-6 col-md-4 col-lg-4 col-xs-4">...</div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-md-4 offset-4 col-lg-6">...</div>
      <div class="col-md-4 col-lg-6">...</div>
      <div class="col-md-4 col-lg-6">...</div>
    </div>
  </div> 
```




### Utilities

Position :
```sh
  <div class="p-r">...</div>
  <div class="p-a">...</div>
  <div class="p-f">...</div>
  <div class="p-f fixed-top">...</div>
  <div class="p-f fixed-bottom">...</div>
```

Display :
```sh
  <div class="d-none">...</div>
  <div class="d-flex">...</div>
  <div class="d-grid">...</div>
  <div class="d-block">...</div>
  <div class="d-inline-block">...</div>
  <div class="d-inline">...</div>
```

Float :
```sh
  <div class="float-none">...</div>
  <div class="float-right">...</div>
  <div class="float-left">...</div>
  <div class="clearfix"></div>
```

Vertical-align :
```sh
  <div class="va-baseline">...</div>
  <div class="va-top">...</div>
  <div class="va-bottom">...</div>
```

Color :
```sh
  <p class="bg-blue text-black">...</p>
  <p class="bg-black text-white">...</p>
  <p class="text-black bg-secondary">...</p>
  <p class="text-white bg-primary">...</p>
  <p class="text-white bg-success">...</p>
```

Width :
```sh
  <div class="w-70">...</div>
  <div class="w-30">...</div>
  <div class="w-50">...</div>
  <div class="w-50">...</div>
  <div class="w-vw-100">...</div>
  <div class="w-auto">...</div>
```
      
Margin & Padding :
```sh
  <p class="p-1">...</p>
  <p class="p-5">...</p>
  <p class="px-auto">...</p>
  <p class="pl-5">...</p>
  <p class="py-2">...</p>

  <p class="m-1">...</p>
  <p class="m-5">...</p>
  <p class="mx-auto">...</p>
  <p class="ml-5">...</p>
  <p class="my-2">...</p>
```

Border :
```sh
  <div class="b-default"></div>
  <div class="bt-default b-black"></div>
  <div class="br-default b-success"></div>
  <div class="bl-default bl-danger"></div>
  <div class="b-none"></div>
```

Overflow :
```sh
  <div class="o-auto">...</div>
  <div class="o-none">...</div>
  <div class="o-scroll">...</div> 
```

Visibility :
```sh
  <div class="v-visible">Lorem ipsum dolor sit.</div>
  <div class="v-hidden">Lorem, ipsum dolor.</div>
  <div class="v-collapse">Lorem ipsum dolor sit.</div>
```

Effect :
```sh
  <div class="box-shadow-default">...</div>
  <div class="box-shadow-sm ">...</div>
  <div class="box-shadow-lg">...</div>

  <div class="rounded-default">...</div>
  <div class="rounded-lg">...</div>
  <div class="rounded-default">...</div>
  <div class="rounded-top-default">...</div>
  <div class="rounded-bottom-lg">...</div>
  <div class="rounded-left-default">...</div>
```




### Utilities flexbox

Flex-direction :
```sh
  <div class="d-flex flex-row-reverse">...</div>
  <div class="d-flex flex-row">...</div>
  <div class="d-flex flex-column">...</div>
  <div class="d-flex flex-column-reverse">...</div>
```

Flex-wrap :
```sh
  <div class="d-flex flex-nowrap">...</div>
  <div class="d-flex flex-wrap">...</div>
  <div class="d-flex flex-wrap-reverse">...</div>
```

Justify-content :
```sh
  <div class="d-flex flex-justify-content-start">...</div>
  <div class="d-flex flex-justify-content-end">...</div>
  <div class="d-flex flex-justify-content-center">...</div>
  <div class="d-flex flex-justify-content-space-between">...</div>
  <div class="d-flex flex-justify-content-space-around">...</div>
  <div class="d-flex flex-justify-content-space-evenly">...</div>
```

Align-items :
```sh
  <div class="d-flex flex-align-items-start">...</div>
  <div class="d-flex flex-align-items-end">...</div>
  <div class="d-flex flex-align-items-center">...</div>
  <div class="d-flex flex-align-items-stretch">...</div>
  <div class="d-flex flex-align-items-baseline">...</div>
```

Align-content :
```sh
  <div class="d-flex flex-align-content-start">...</div>
  <div class="d-flex flex-align-content-end">...</div>
  <div class="d-flex flex-align-content-center">...</div>
  <div class="d-flex flex-align-content-space-between">...</div>
  <div class="d-flex flex-align-content-space-around">...</div>
```

Align-self :
```sh
  <div class="d-flex flex-align-self-auto">...</div>
  <div class="d-flex flex-align-items-start">...</div>
  <div class="d-flex flex-align-items-end">...</div>
  <div class="d-flex flex-align-items-center">...</div>
  <div class="d-flex flex-align-items-stretch">...</div>
  <div class="d-flex flex-align-items-baseline">...</div>
```

Flex-grow and flex-shrink:
```sh
  <div class="d-flex flex-grow-0">...</div>
  <div class="d-flex flex-grow-1">...</div>
  
  <div class="d-flex flex-shrink-0">...</div>
  <div class="d-flex flex-shrink-1">...</div>
```

Flex:
```sh
  <div class="d-flex flex-fill">...</div>
```




### Text

Font-weight :
```sh
  <p class="font-weight-normal"></p>
  <p class="font-weight-light"></p>
  <p class="font-weight-bold"></p>
```

Font-style :
```sh
  <p class="font-style-normal">...</p>
  <p class="font-style-italic">...</p>
```

White-space :
```sh
  <p class="text-normal">...</p>
  <p class="text-nowrap">...</p>
  <p class="text-pre">...</p>
  <p class="text-prewrap">...</p>
  <p class="text-preline">...</p>
```

Text-align :
```sh
  <p class="align-left">...</p>
  <p class="align-center">...</p>
  <p class="align-right">...</p>
  <p class="align-justify">...</p>
```

Text-transform :
```sh
  <p class="text-none">...</p>
  <p class="text-lowercase">...</p>
  <p class="text-capitalise">...</p>
  <p class="text-uppercase">...</p>
```

Text-decoration :
```sh
  <p class="text-decoration-none">...</p>
  <p class="text-decoration-underline">...</p>
```

Text-break :
```sh
  <p class="text-break">...</p> -->
```




### Content

Lists :
```sh
  <ul class="list-unstyled">
    <li>...</li>
    <li>...</li>
    <li>...</li>
  </ul>

  <ul>
    <li class="list-inline-item">...</li>
    <li class="list-inline-item">...</li>
    <li class="list-inline-item">...</li>
  </ul>
```

Table :
```sh
  <table class="table table-striped table-bg-primary table-color-white table-hover">
    <thead>
      ...
    </thead>

    <tbody>
      ...
    </tbody>
  </table>
```

Image :
```sh
  <img src="image.jpg" class="img-responsive" alt="">
```

Figure :
```sh
  <figure>
    <img src="image.jpg" class="figure-img img-responsive" alt="">
    <figcaption class="figure-caption bg-dark align-center">...</figcaption>
  </figure>
```

Button :
```sh
  <button class="btn btn-primary">button</button>
  <button class="btn btn-danger">button</button>
  <button class="btn btn-success">button</button>
  <button class="btn btn-blue">button</button>
  <button class="btn btn-black">button</button>

  <button class="btn btn-sm btn-primary">button</button>
  <button class="btn btn-lg btn-primary">button</button>

  <button class="btn btn-block btn-primary">button</button>

  <button class="btn btn-link btn-primary">button</button>
```

Form :
```sh
  <div class="container">
    <form>
      <div class="form-row">
        <div class="col">
          <input type="text" class="form-control" placeholder="First name">
        </div>
        <div class="col">
          <input type="text" class="form-control" placeholder="Last name">
        </div>
      </div>

      <div class="form-group">
        <label>Email</label>
        <input type="email" class="form-control" placeholder="Enter email">
      </div>

      <div class="form-group">
        <label class="col-form-label-lg">Password</label>
        <input type="password" class="form-control form-control-lg" placeholder="Password">
      </div>

      <div class="form-group">
        <label>Email</label>
        <input type="email" class="form-control form-control-sm" placeholder="Enter email">
      </div>

      <div class="form-group">
        <label class="col-form-label-sm">Password</label>
        <input type="password" class="form-control form-control-sm" placeholder="Password">
      </div>

      <div class="form-check form-check-inline">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox1" value="option1">
        <label class="form-check-label">1</label>
      </div>
      <div class="form-check form-check-inline">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox2" value="option2">
        <label class="form-check-label">2</label>
      </div>
      <div class="form-check form-check-inline">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox3" value="option3" disabled>
        <label class="form-check-label">3 (disabled)</label>
      </div>

      <div class="form-group">
        <label>select</label>
        <select class="form-control">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </div>
      
      <div class="form-group">
        <label>multiple select</label>
        <select multiple class="form-control">
          <option>1</option>
          <option>2</option>
          <option>3</option>
          <option>4</option>
          <option>5</option>
        </select>
      </div>

      <div class="form-group">
        <label>file input</label>
        <input type="file" class="form-control-file">
      </div>

      <div class="form-group">
        <label>Range input</label>
        <input type="range" class="form-control-range">
      </div>

      <button type="submit" class="btn btn-blue text-white">Submit</button>
    </form>
  </div>
```
