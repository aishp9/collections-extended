.. py:currentmodule:: collections_extended

Change Log
==========

Version 2.0.0
-------------

Unreleased

* Added :class:`IndexedDict`
* Improve efficiency for large bag operations
* Add :meth:`setlist.swap`
* Add :meth:`bag.count`, :class:`CountsView` & :class:`UniqueElementsView`
* Add :meth:`bag.issubset` and :meth:`issuperset`
* Add support for Python 3.8
* Drop support for Python 2.6, 2.7, 3.3, 3.4
* Add :class:`Sentinel`
* When multiplying bags, the cartesian product creates a tuple instead of adding
    the elements.
* Make :class:`MappedRange` a class instead of a namedtuple
* Add change log
* bags no longer inherit from Set
    * can no longer compare as equal to Sets

Version 1.0.2
-------------
