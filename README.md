P2.6 - The Finite Element Method Using deal.II
===============================================
## Lecturers: Jean-Paul Pelteret and Luca Heltai

This repository contains the assignments and workspaces for the
course P2.6

Running deal.II on Ulysses
==========================

If you have access to Uylsses, you can add the following to your `.bashrc`:

	. /home/mathlab/dealii-trilinos-p4est/set_up_dealii.sh

This will export all libraries required by `deal.II`, and the latest stable  version of `deal.II` (v8.5.0).

Running deal.II using docker
============================

```
docker run -t -i dealii/dealii:v8.5.0-gcc-mpi-fulldepscandi-debugrelease

```

License
=======
The course content for _P2.6 - The Finite Element Method Using deal.II_ is licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.
