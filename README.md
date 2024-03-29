sa_python_anaconda
==================
[![Build Status](https://github.com/softasap/sa-python-anaconda/workflows/CI/badge.svg?event=push)](https://github.com/softasap/sa-python-anaconda/actions?query=workflow%3ACI)
[![Build Status](https://travis-ci.org/softasap/sa-python-anaconda.svg?branch=master)](https://travis-ci.org/softasap/sa-python-anaconda)



Example of usage:

Simple

```YAML

     - {
         role: "sa_python_anaconda"
       }


```

Advanced

```YAML

     - {
         role: "sa_python_anaconda"
       }


```

Credits:

 conda module for python:  https://github.com/UDST/ansible-conda , see License for module under library/License.txt


Usage with ansible galaxy workflow
----------------------------------

If you installed the `sa_python_anaconda` role using the command


`
   ansible-galaxy install softasap.sa_python_anaconda
`

the role will be available in the folder `library/softasap.sa_python_anaconda`
Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa_python_anaconda"
       }

```




Copyright and license
---------------------

Code is dual licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) and the [MIT License] (http://opensource.org/licenses/MIT). Choose the one that suits you best.

Reach us:

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)

Join gitter discussion channel at [Gitter](https://gitter.im/softasap)

Discover other roles at  http://www.softasap.com/roles/registry_generated.html

visit our blog at http://www.softasap.com/blog/archive.html 
