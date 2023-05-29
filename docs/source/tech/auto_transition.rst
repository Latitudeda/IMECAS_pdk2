auto_transition.py
====================

Define the transition between different waveguide type. In IMECAS pdk, there are two types of waveguides (Channel and Rib) and ``AutoTransition`` allows the layout to auto-generate transitions between them. The transition components are defined by IMECAS, which are ``TR450_rib650`` and ``TR380_Rib580``.

Users are allowed to define the transition components  and set ``DEFAULT`` to their own specific transition policy. Please see ``gpdk > components > transition`` for more examples.