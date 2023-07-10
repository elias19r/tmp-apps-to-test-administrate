# tmp-apps-to-test-administrate

## Install Ruby and Rails

```
asdf local ruby 3.0.6

gem install rails -v 6.0.6.1
gem install rails -v 6.1.7.4
gem install rails -v 7.0.6
```

## Rails 6 + webpack

### rails-6-webpack

```
rails _6.0.6.1_ new rails-6-webpack
```

## Rails 6.1 + webpack

### rails-6-1-webpack

```
rails _6.1.7.4_ new rails-6-1-webpack
```

## Rails 7 + importmap

### rails-7-importmap-tailwind

```
rails _7.0.6_ new rails-7-importmap-tailwind \
  --javascript=importmap \
  --css=tailwind
```

### rails-7-importmap-bootstrap

```
rails _7.0.6_ new rails-7-importmap-bootstrap \
  --javascript=importmap \
  --css=bootstrap
```

### rails-7-importmap-bulma

```
rails _7.0.6_ new rails-7-importmap-bulma \
  --javascript=importmap \
  --css=bulma
```

### rails-7-importmap-postcss

```
rails _7.0.6_ new rails-7-importmap-postcss \
  --javascript=importmap \
  --css=postcss
```

### rails-7-importmap-sass

```
rails _7.0.6_ new rails-7-importmap-sass \
  --javascript=importmap \
  --css=sass
```

## Rails 7 + webpack

### rails-7-webpack-tailwind

```
rails _7.0.6_ new rails-7-webpack-tailwind \
  --javascript=webpack \
  --css=tailwind
```

### rails-7-webpack-bootstrap

```
rails _7.0.6_ new rails-7-webpack-bootstrap \
  --javascript=webpack \
  --css=bootstrap
```

### rails-7-webpack-bulma

```
rails _7.0.6_ new rails-7-webpack-bulma \
  --javascript=webpack \
  --css=bulma
```

### rails-7-webpack-postcss

```
rails _7.0.6_ new rails-7-webpack-postcss \
  --javascript=webpack \
  --css=postcss
```

### rails-7-webpack-sass

```
rails _7.0.6_ new rails-7-webpack-sass \
  --javascript=webpack \
  --css=sass
```

## Rails 7 + esbuild

### rails-7-esbuild-tailwind

```
rails _7.0.6_ new rails-7-esbuild-tailwind \
  --javascript=esbuild \
  --css=tailwind
```

### rails-7-esbuild-bootstrap

```
rails _7.0.6_ new rails-7-esbuild-bootstrap \
  --javascript=esbuild \
  --css=bootstrap
```

### rails-7-esbuild-bulma

```
rails _7.0.6_ new rails-7-esbuild-bulma \
  --javascript=esbuild \
  --css=bulma
```

### rails-7-esbuild-postcss

```
rails _7.0.6_ new rails-7-esbuild-postcss \
  --javascript=esbuild \
  --css=postcss
```

### rails-7-esbuild-sass

```
rails _7.0.6_ new rails-7-esbuild-sass \
  --javascript=esbuild \
  --css=sass
```

## Rails 7 + rollup

### rails-7-rollup-tailwind

```
rails _7.0.6_ new rails-7-rollup-tailwind \
  --javascript=rollup \
  --css=tailwind
```

### rails-7-rollup-bootstrap

```
rails _7.0.6_ new rails-7-rollup-bootstrap \
  --javascript=rollup \
  --css=bootstrap
```

### rails-7-rollup-bulma

```
rails _7.0.6_ new rails-7-rollup-bulma \
  --javascript=rollup \
  --css=bulma
```

### rails-7-rollup-postcss

```
rails _7.0.6_ new rails-7-rollup-postcss \
  --javascript=rollup \
  --css=postcss
```

### rails-7-rollup-sass

```
rails _7.0.6_ new rails-7-rollup-sass \
  --javascript=rollup \
  --css=sass
```
