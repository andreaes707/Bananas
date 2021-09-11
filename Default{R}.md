# Revisions
## Navigation

### R# .02
```HTML
      <!-- Site Navigation Here  -->
  <nav id="Top" class="navbar navbar-expand-lg text-align-center align-items-center justify-content-evenly navbar-dark bg-danger">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Site Navigation</a>
      <button class="btn btn-lg btn-outline-dark navbar-toggler" type="button" name="navButton" data-bs-toggle="collapse" data-bs-target="#navBar" aria-controls="navBar" aria-expanded="false" aria-label="Toggle Navigation">
        <i class="fas fa-biohazard"></i>
      </button>
      <div id="navBar" class="collapse navbar-collapse nav-justified text-align-center align-items-center justify-content-center">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active bg-dark" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item dropend">
            <a id="blogDrop" class="nav-link dropdown-toggle" role="button" href="#" data-bs-toggle="dropdown" aria-expanded="false">Blog</a>
            <ul class="dropdown-menu text-center mx-auto" aria-labelledby="blogDrop">
              <li><a class="dropdown-item" href="../Master02/Blog/Greet/blogGreet.html">Blog</a></li>
              <li><a class="dropdown-item" href="../Master02/Blog/Article/Articles.html">Articles</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="../Master02/Blog/Quotes/Quotes.html">Quotes</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="../Master02/Blog/Guide/Guide.html">Guide</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="../Master02/Blog/Resources/Resources.html">Resources</a>
          </li>
          <li class="nav-item dropend">
            <a id="photoDrop" class="nav-link dropdown-toggle" role="button" href="#" data-bs-toggle="dropdown" aria-expanded="false">Photography</a>
            <ul class="dropdown-menu text-center mx-auto" aria-labelledby="photoDrop">
              <li><a class="dropdown-item" href="../Master02/Blog/Photography/Gallery/Gallery.html">Gallery</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="../Master02/Blog/Photography/Exercises/Exercises.html">Exercises</a></li>
            </ul>
          </li>
          <li class="nav-item dropend">
            <a id="missionDrop" class="nav-link dropdown-toggle" role="button" href="#" data-bs-toggle="dropdown" aria-expanded="false">Mission</a>
            <ul class="dropdown-menu text-center mx-auto" aria-labelledby="missionDrop">
              <li><a class="dropdown-item" href="../Master02/Blog/Mission/Vision/missionStart.html">Vision</a></li>
              <li><a class="dropdown-item" href="../Master02/Blog/Mission/About/aboutMe.html">About</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="../Master02/Blog/Mission/Templates/Templates.html">Templates</a></li>
            </ul>
          </li>
        </ul>
      </div>
      <button class="btn btn-outline-light" type="button" name="button" aria-controls="Bottom" aria-label="Bottom"><i class="fas fa-angle-double-down"></i></button>
    </div>
  </nav>
 ```
### R# .01
```HTML
      <!-- Navigation Here  -->
  <nav class="navbar navbar-expand-lg text-align-center align-items-center justify-content-evenly navbar-dark bg-danger">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Site Navigation</a>
      <button class="btn btn-lg btn-outline-dark navbar-toggler" type="button" name="navButton" data-bs-toggle="collapse" data-bs-target="#navBar" aria-controls="navBar" aria-expanded="false" aria-label="Toggle Navigation">
        <i class="fas fa-biohazard"></i>
      </button>
      <div id="navBar" class="collapse navbar-collapse nav-justified text-align-center align-items-center justify-content-center">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active bg-dark" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item dropend">
            <a id="blogDrop" class="nav-link dropdown-toggle" role="button" href="#" data-bs-toggle="dropdown" aria-expanded="false">Blog</a>
            <ul class="dropdown-menu text-center mx-auto" aria-labelledby="blogDrop">
              <li><a class="dropdown-item" href="/Master02/Blog/Greet/blogGreet.html">Blog</a></li>
              <li><a class="dropdown-item" href="/Master02/Blog/Article/Articles.html">Articles</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="/Master02/Blog/Quotes/Quotes.html">Quotes</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="/Master02/Blog/Guide/Guide.html">Guide</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/Master02/Blog/Resources/Resources.html">Resources</a>
          </li>
          <li class="nav-item dropend">
            <a id="photoDrop" class="nav-link dropdown-toggle" role="button" href="#" data-bs-toggle="dropdown" aria-expanded="false">Photography</a>
            <ul class="dropdown-menu text-center mx-auto" aria-labelledby="photoDrop">
              <li><a class="dropdown-item" href="/Master02/Blog/Photography/Gallery/Gallery.html">Gallery</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="/Master02/Blog/Photography/Exercises/Exercises.html">Exercises</a></li>
            </ul>
          </li>
          <li class="nav-item dropend">
            <a id="missionDrop" class="nav-link dropdown-toggle" role="button" href="#" data-bs-toggle="dropdown" aria-expanded="false">Mission</a>
            <ul class="dropdown-menu text-center mx-auto" aria-labelledby="missionDrop">
              <li><a class="dropdown-item" href="/Master02/Blog/Mission/Vision/missionStart.html">Vision</a></li>
              <li><a class="dropdown-item" href="/Master02/Blog/Mission/About/aboutMe.html">About</a></li>
              <li class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="/Master02/Blog/Mission/Templates/Templates.html">Templates</a></li>
            </ul>
          </li>
        </ul>
      </div>
      <button class="btn btn-outline-light" type="button" name="button" aria-controls="#Bottom" aria-label="Bottom"><i class="fas fa-angle-double-down"></i></button>
    </div>
  </nav>
```

- - - -

## Head
### R# .02
```HTML
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,shrink-to-fit=no;">
    <meta name="developer/author" content="Alison_Concordia~{Andrea.Estrada}">
    <meta name="description" content="Basic Head Template Without Footer">
    <title>Head</title>
    <link rel="stylesheet" href="../Master02/Styles/FA/css/all.min.css">
    <link rel="stylesheet" href="../Master02/Styles/Bv5/css/bootstrap.min.css">
    <link rel="stylesheet" href="../Master02/Styles/Bv5/css/bootstrap-grid.min.css.map">
</head>
```
### R# .01
```HTML
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width;shrink-to-fit=no;">
    <meta name="developer/author" content="Alison Concordia">
    <meta name="description" content="Basic Head Template; No footer.">
    <title>Navigation</title>
    <link rel="stylesheet" href="/Master02/Styles/FA/css/all.min.css">
    <link rel="stylesheet" href="/Master02/Styles/Bv5/css/bootstrap.min.css">
    <link rel="stylesheet" href="/Master02/Styles/Bv5/css/bootstrap-grid.min.css.map">
  </head>
  ```
