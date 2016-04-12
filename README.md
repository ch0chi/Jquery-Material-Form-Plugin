# Jquery Material Form Plugin

### Version
1.0

### Getting Started

Setup for the plugin is simple, but first it does require that [Twitter Bootstrap](http://www.getbootstrap.com), [Jquery](https://jquery.com/download/), and *(optional)* [Font Awesome](http://fortawesome.github.io/) be installed.

Okay, once you've got the prerequisites installed, you're ready to move on to the actual installation. Simply add ```<link rel="stylesheet" href="materialForm.css">``` to the header and ```<script src="materialForm.js"></script>``` to the end of your body.


### Installation

Copy the following to the desired location of the form:
```sh
<div class="container" id="formOutterWrapper">
        <div class="container" id="formInnerWrapper">
                <form id="materialForm" class="form" method="post" action="" role="form" autocomplete="off">
                    <div class="form-group">
                        <div class="col-xs-6">
                            <label class="labels" for="firstName">First Name</label>
                            <input type="text" class="formInput" id="firstName" name="firstName">
                        </div>
                        <div class="col-xs-6">
                            <label class="labels" for="lastName">Last Name</label>
                            <input type="text" class="formInput" id="lastName" name="lastName">
                        </div>
                    </div>
                    <div class="form-group">
                        <div class="col-xs-6">
                            <label class="labels" for="email">Email</label>
                            <input type="text" class="formInput" id="email" name="email">
                        </div>
                        <div class="col-xs-6">
                            <label class="labels" for="phone">Phone</label>
                            <input type="tel" class="formInput" id="phone" name="phone">
                        </div>
                    </div>
                    <div class="form-group">
                        <div class="col-xs-12">
                            <label class="labels" for="description">Project Description</label>
                            <input type="text" class="formInput" id="description" name="description">
                        </div>
                    </div>
                    <div class="form-group">
                        <div class="col-xs-12">
                            <button type="button" class="btn btn-primary green flatButton" id="submit">Submit</button>
                        </div>
                    </div>
                </form>
        </div>
    </div>
```
That's it!


License
----
MIT

