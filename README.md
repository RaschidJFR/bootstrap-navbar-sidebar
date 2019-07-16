# bootstrap-navbar-sidebar

Bootstrap navbars fixed to left or right

Use classic Bootstrap navbar as sidebar, on left or right side.

[Demo](https://mladenplavsic.github.io/bootstrap-navbar-sidebar/)

For Bootstrap v3.* check the `bootstrap-v3` branch 

[![Bootstrap navbars fixed to left or right](https://github.com/mladenplavsic/bootstrap-navbar-sidebar/raw/master/resources/bootstrap-navbar-sidebar-demo.gif)](https://mladenplavsic.github.io/bootstrap-navbar-sidebar/)

## Usage
1. Install: `$npm i bootstrap-navbar-sidebar`
2. Import into your main sass file (or any other convenient): 

```
@import 'node_modules/bootstrap-navbar-sidebar/dist/navbar-fixed-left.min'; // or navbar-fixed-right.min
```

3. Add the class `fixed-left`/`fixed-right` to your bootstrap navbar:

```
<nav class="navbar navbar-expand-lg navbar-dark bg-secondary fixed-left">
  ...
</nav>
```
