Components
==========

---

Grid
----

The grid system in use is simple to use, and follows a similar format
to bootstrap.

    <div class="row">
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
    </div>

<div class="row showGrid">
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
</div>

It is also very easy to handle overflows

    <div class="row">
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>     
        <div class="col-xs-12 col-sm-3">
            .col-xs-12.col-sm-3
        </div>     
        <div class="col-xs-12 col-sm-9">
            <div class="col-xs-12 col-sm-6">
              .col-xs-12.col-sm-3 > .col-xs-12.col-sm-6
            </div>
            <div class="col-xs-12 col-sm-6">
              .col-xs-12.col-sm-3 > .col-xs-12.col-sm-6
            </div>
        </div>
    </div>

<div class="row showGrid">
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>     
    <div class="col-xs-12 col-sm-3">
        .col-xs-12.col-sm-3
    </div>     
    <div class="col-xs-12 col-sm-9">
        <div class="col-xs-12 col-sm-6">
          .col-xs-12.col-sm-3 > .col-xs-12.col-sm-6
        </div>
        <div class="col-xs-12 col-sm-6">
          .col-xs-12.col-sm-3 > .col-xs-12.col-sm-6
        </div>
    </div>
</div>

---

Buttons
-------

It is simple to add button in `Framed`

    <a class="btn plain" href="#">Example button</a>

* <a class="btn plain" href="#">plain</a>
* <a class="btn dark" href="#">dark</a>
* <a class="btn info" href="#">info</a>
* <a class="btn warn" href="#">warn</a>
* <a class="btn danger" href="#">danger</a>
* <a class="btn regal" href="#">regal</a>

It is also possible to modify the size of buttons by typography modifiers
like `sm`, `md`, `lg` and `xl`.

* <a class="btn plain sm" href="#">sm</a>
* <a class="btn plain md" href="#">md</a>
* <a class="btn plain lg" href="#">lg</a>
* <a class="btn plain xl" href="#">xl</a>

---

Forms
-----

Forms are as simple to add as they are usually, form styles have been
overridden