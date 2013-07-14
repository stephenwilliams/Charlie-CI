Charlie CI
=================

Charlie CI is a continuous integration server written in Java.
Inspired by Jenkins CI, Charlie CI strives to have a strong,
expansive, and well documented API to allow plugins to do
as much as possible. On its own Charlie CI will not do much
of anything at all as it needs plugins to add any functionality
beyond the core system and API.

Charlie CI is still in development. You can check progress
here.

Charlie CI API is the API plugins use to integrate and interact with
Charlie CI.

Copyright &copy; 2013, Stephen Williams (alta189) <http://alta189.com/>

Downloads
-----------------

The latest Charlie CI source can be found [here][Github] and the latest Charlie CI API source can be found [here][API Github].
No builds are currently availble. Builds will most likely be posted when Charlie CI hits alpha.

License
-----------------
Charlie CI and Charlie CI API are both licensed under the GNU Lesser General Public License Version 3.

Issues and Roadmap
-----------------
You can submit issues, bugs, and ideas to our [issue tracker][Issues]. You can also find our roadmap/milestones [here][Milestones].

Compiling
-----------------
Charlie CI uses [Apache Maven][Maven] to handle dependencies and compilation
* Install [Maven][Maven Download]
* Checkout this repo and run: `mvn clean package`
* Complied source should be in the `target` folder

[alta189 site]: http://alta189.com/
[Github]: http://github.com/alta189/Charlie-CI
[API Github]: http://github.com/alta189/Charlie-CI-API
[Issues]: https://github.com/alta189/Charlie-CI/issues
[Milestones]: https://github.com/alta189/Charlie-CI/issues/milestones
[License]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Maven]: http://maven.apache.org/
[Maven Download]: http://maven.apache.org/download.html


