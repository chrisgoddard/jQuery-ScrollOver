jQuery-ScrollOver
=================

Simple jQuery plugin for enabling actions on scroll over element. Allows you to assign functions to before, over and after an element has been scrolled to.

Functions work both when scrolling down to an element and scrolling back up to the element.

By default function will fire only once during a single top-to-bottom scroll, but events will refire if user scrolls back up the page.

Usage
=====

$(element).scrollover({

  before: function(elem){
  
    /* Function runs when scrolled above element */
  
  }, 
  
  over: function(elem){
    /* Function runs when scrolled over an element */
  },
  
  after: function(elem){
    /*  Function runs when scrolled after an element */
  },
  
  /* options */
  
  motion : false, // Default: false, set to true to have function fire on every scroll event
  trackElem : 'body', Default: 'body', element the scroll scroll event is tracked from

});
