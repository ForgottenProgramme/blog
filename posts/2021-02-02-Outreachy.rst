.. post:: 2021-02-02
   :tags: Outreachy
   :author: viniciusdc
   :redirect: 2021/02/02/Outreachy

Conda-forge Outreachy
=====================

Conda-forge is participating for this round of Outreachy. The goal of
the program is to increase participation from under-represented groups
in free and open source software. It is a project of the Software
Freedom Conservancy.

Participant Application Process:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

First, please review the Outreachy Eligibility and Application
Information page to learn more about eligibility for Outreachy.

Steps for applicants to conda-forge:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

| Confirm your eligibility on the outreachy site
| Look at the Conda-forge projects available on the Outreachy site,
consider your options, and if you have questions, communicate with the
project mentors.

| Begin by contributing to the project. Most projects will describe how
to make your first contribution. As you make contributions, record them
on the Outreachy site. Codetribute may help you find good tasks to work
on. For many applicants, this is the most valuable part of the
experience!
| Once you have made a few contributions, begin to write your
application. Ask the mentors to review the application before you submit
it.

Participant Expectations
~~~~~~~~~~~~~~~~~~~~~~~~

You will be working full-time on your project for three months. You will
meet with your mentor(s) frequently and participate in the open-source
development process -- writing code, reviewing code, testing, and so on.
You will be expected to write a blog entry each week.

Project Contribution Information
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

As part of the application process, all applicants must make at least
one contribution to be accepted as an intern for this project. Only
applicants who make a contribution will be eligible to be accepted as
interns.

While we don't have one we highly recommend the first time contributor
to be a conda user and/or submit a package to conda-forge via
`staged-recipes <https://github.com/conda-forge/staged-recipes>`__. That
will ensure the contributor understands the value of what we do and
means that they are willing to participate in our community.

Applicants can contribute to this project through the `project
repository or contribution
page <https://conda-forge.org/#contribute>`__. The project uses an
`issue
tracker <https://github.com/conda-forge/conda-forge.github.io/issues>`__
to keep information about bugs to fix, project features to implement,
documentation to write, and more. Applicants can look for
newcomer-friendly issues to use for their first contributions by looking
for the following issue tags in the project issue
`tracker <https://github.com/conda-forge/conda-forge.github.io/issues>`__:
Docs, Good first issue

We here at `conda-forge <https://conda-forge.org/#contribute>`__ have a
large number of potential Outreachy endeavors around documentation,
maintenance and development. These tasks are high-impact, affecting the
entire conda-forge ecosystem. They also cover multiple systems including
databases, conda's CDN provider, continuous integration providers, and
user interactions on GitHub.

How do I work with the conda-forge community?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Outreachy applicants can get help and feedback from both mentors and
community members. Community members discuss their contributions in a
public chat. Outreachy applicants can often learn from those
discussions.

Please introduce yourself on the public project chat:

Gitter - `Follow this
link <https://gitter.im/conda-forge/conda-forge.github.io>`__ to join
this project's public chat.

Outreachy mentors will often be in the community public chat. The
project mentor's usernames are: ``@viniciusdc``.

Here are some read-to-go ways you can get started contributing on your own.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

-  Find an open issue to tackle or report a bug to the issue tracker;
-  Don’t be afraid to communicate: Ask if you can help write a new
   feature or help Automate project setups;
-  Improving current tooling and testing features is always welcome.

As this project main goals is enhancing our current documentation, here
are some preliminary tasks that you can inspect to get ideas:

-  Write and improve the project’s documentation;
-  Link to duplicate issues, and suggest new issue labels, to keep
   things organized;
-  Go through open issues and suggest closing old ones;
-  Ask clarifying questions on recently opened issues to move the
   discussion forward;
-  We also have issues regarding the main functionalities of our bot, in
   particular the autotick bot. You could find some new information or
   ideas for your contributing proposals.

Good starter tasks:
~~~~~~~~~~~~~~~~~~~

Small Starter Tasks
^^^^^^^^^^^^^^^^^^^

As with most organizations, there are lots of small issues that need
addressing usually related to problems such as bad recipes, old
documentation and others. These will make good first issues to resolve
or "update". This will also be an opportunity to familiarise yourself
with the conda-forge environment.

Larger tasks
^^^^^^^^^^^^

There are a few potential larger tasks that can come after a few smaller
task contributions. These are included into our three main bases:

-  `Users <https://conda-forge.org/docs/user/00_intro.html>`__: In this
   case, some good starter tasks are mainly checking the actual contents
   of conda-forge users documentations, and ideas to better express it's
   contents.

-  `Maintainers <https://conda-forge.org/docs/maintainer/00_intro.html>`__:
   There are a bunch of missed topics in this area, some information
   have to be updated or rewritten for better understanding. Writing a
   complete guide containing the actual steps and standard model for a
   package recipe, building process (just a simple discussion) and how
   conda-forge bot recognize defective licenses, recipes and packages in
   general is highly welcomed. For further understanding of the general
   system check `this
   link <https://conda-forge.org/docs/maintainer/infrastructure.html>`__.

   -  It can be funny to say, but lots of helpful ideas and bug
      solutions appear on our gitter channel, so if you have time to
      write guides about them... it's also an incredible task.

-  `And
   organization <https://conda-forge.org/docs/orga/00_intro.html>`__ Our
   environment is changing everyday, because of that a lot of
   information is lost in this process or even worse, not documented at
   all! which leads to some difficulties inserting new members to
   develop and further enhance the current process.

   -  The related work on this matter is highly welcomed and for a
      better grasp of the situation you can start with this
      `guideline <https://conda-forge.org/docs/orga/guidelines.html>`__
      and read some of our posts in our
      `blog <https://conda-forge.org/blog/blog/>`__
   -  Revitalizing ideas/projects for the conda-forge blog are
      definitely welcomed;
   -  Currently we have some interesting projects going on inside our
      ecosystem, which in return will need good documentation... Some of
      the projects conda-forge is affiliated include the `auto-tick
      bot <https://github.com/regro/cf-scripts>`__,
      `symbol-exporter <https://github.com/symbol-management/symbol-exporter>`__
      and a new service we are eager to start developing is the
      `distributed-bot <https://github.com/regro/cf-scripts/issues/1367>`__.
      All of them have a great coverage of subjects and lots of people
      to help and give advice about the service structure and
      functionalities.

Improving the documentation
~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can help improve the documentation as it is version-controlled in
the conda-forge.github.io repository on GitHub. The source text is
stored there in the ``src/subdirectory`` and is formatted using
`Python’s reStructuredText
system <https://wiki.python.org/moin/reStructuredText>`__.

You can propose quick edits directly through the GitHub website, if you
have an account there — for instance, this
`link <https://github.com/conda-forge/conda-forge.github.io/edit/master/src/user/contributing.rst>`__
will take you directly to a web-based editor for this section page in
our
`docs <https://conda-forge.org/docs/user/contributing.html#improve-docs>`__.
In general, the file corresponding to each page in the GitHub browser
has a little pencil icon in its top-right that lets you open it up for
editing.

The more manual process is as follows:

-  Fork the conda-forge.github.io repository to your own GitHub user
   account.

-  Clone that fork onto your computer.

-  Check out a new branch deriving from master to do your work.

-  Make and commit your changes.

-  Submit a pull request to the main repository proposing your changes.

Happy editing!
