"Virtual_dom: a virtual DOM diffing library"
============================================

This library is an OCaml wrapper of Matt Esch's [[https://github.com/Matt-Esch/virtual-dom][virtual-dom library]].
It provides a simple, immutable representation of a desired state of
the DOM, as well as primitives for updating the real DOM in the
browser to match that, both by slamming the entire DOM in place, and
by computing diffs between successive virtual-DOMs, and applying the
resulting patch to the real DOM.
