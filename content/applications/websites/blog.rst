====
Blog
====

**Odoo Blog** lets you manage blog pages and posts, and customize them with the website builder.

.. seealso::
   `Odoo Tutorials: Blogs [video] <https://www.odoo.com/slides/slide/blogs-6935>`_

Blog posts
==========

To create a blog post, click :guilabel:`New` and click :guilabel:`Blog Post`. Select a
:ref:`blog <blog/blog pages>`, define a :guilabel:`Blog Post Title` and click :guilabel:`Save`.
Write the post's content and customize it using the website builder.

To publish a post, toggle the :guilabel:`Unpublished` switch in the top-right corner of the page.

.. tip::
   - Use `/` to activate the :ref:`Powerbox <Powerbox>` which displays some functions such as
     :doc:`AI <../../../applications/productivity/ai/agents>` to generate and structure the content.
   - Use the :ref:`Text editor toolbar<essentials/html_editor/toolbar>` by hovering the mouse over
     the selected text to edit its format.

Customize blog posts
--------------------

To customize the layout of all blog posts, open one and click :menuselection:`Edit --> Style`.
Different options can be used to customize the posts:

- :guilabel:`Layout`: displays the title inside or above the cover.
- :guilabel:`Increase Readability`: Enhances text appearance for better reading comfort without
  changing the content.
- :guilabel:`Sidebar`: displays archives, authors, blogs list, social networks, next article and
  comments.
- :guilabel:`Archive`: enables filtering posts by selected month.
- :guilabel:`Author`: displays the post author.
- :guilabel:`Blog List`: displays links to all the blogs.
- :guilabel:`Share Links`: displays share buttons to several social networks.
- :guilabel:`Breadcrumb`: displays the breadcrumb trail.
- :guilabel:`Bottom`: click the :guilabel:`Next Article` to hide or display the next post at the
   end of the page, and click the :guilabel:`Comments` enables or disable visitors to add comments.

To add tags or customize the cover of a specific post, click the cover and use the following
settings under the :guilabel:`Blog Post Cover` section:

- :guilabel:`Tags`: select existing tags to be displayed below blog posts.
- :guilabel:`Background`: adds a :ref:`theme color <website/themes/colors>`, a picture or a video as
  the post's cover's background.
- :guilabel:`Size`: select the size of the cover (:guilabel:`Full screen`; :guilabel:`Half screen`,
  or :guilabel:`Fit text`)
- :guilabel:`Filter Intensity`: choose the intensity of the cover's color.
  (:guilabel:`Low`, :guilabel:`Medium`, :guilabel:`High`) or disable it by selecting :guilabel:`No filter`.

After applying the desired changes, click :guilabel:`Save`.

.. tip::
   - To change the author of the blog post, go to :menuselection:`Edit -> style` and click the author
     under the blog post or the blog page. Then, go to the website builder, under the :guilabel:`Block` section and
     select the author in the :guilabel:`Contact` field.
   - Illustrate your articles with copyright-free images from :doc:`Unsplash
     </applications/general/integrations/unsplash>`.
   - Use :ref:`Plausible <analytics/plausible>` to keep track of the traffic on your blog.
   - Customize blog building blocks through the website editor. For e.g., filter by the
     :guilabel:`Latest blog posts` or :guilabel:`Most viewed blog posts` and determine which blog
     to display in the building block.

.. seealso::
   :doc:`Building block documentation <../../../applications/websites/website/web_design/building_blocks>`

.. _blog/tags:

Tags
~~~~

Tags let visitors filter blog posts that share a specific tag. They are displayed at the
bottom of each post.



To create a tag, go to :menuselection:`Website --> Configuration --> Tags` and click
:guilabel:`New`. Fill in the:

- :guilabel:`Name`.
- :ref:`Category <blog/tag category>`.
- :guilabel:`Color`.
- :guilabel:`Used in`: to apply tags to existing blog posts, click :guilabel:`Add a line`,
  select the posts, and click :guilabel:`Select`.

To manage the appearance of the tags, click :menuselection:`Edit --> Style` and enable the
:guilabel:`Sidebar`. On the :guilabel:`Posts List` section, enable or disable the
:guilabel:`Teaser & Tags` option.

Add and create tags directly from posts by clicking :menuselection:`Edit --> Style` and
select the post's cover. Under :guilabel:`Tags`, click :guilabel:`Choose a record...`, and select
or create a tag. Or create a tag by writing the name in the search bar and clicking
:guilabel:`Create "..."`.

.. _blog/tag category:

Tag category
************

Tag categories let you organize tags displayed on the sidebar into groups.

.. image:: blog/tag-categories.png
    :alt: tag categories

To create tag categories, go to :menuselection:`Website --> Configuration --> Tag
Categories` and click :guilabel:`New`.

.. _blog/blog pages:

Blog landing pages
==================

To create or edit a blog, go to :menuselection:`Website --> Configuration --> Blogs`. Click
:guilabel:`New`, select the :guilabel:`Blog` and define the :guilabel:`Blog Subtitle`.

.. note::
   With two or more blogs, the blog landing page (/blog) aggregates posts from all blogs and lets
   visitors choose which blog to view.

The :guilabel:`Blog` menu is added to the website's menu the first time a blog is created and
gathers all the blogs and their posts.

Customize blog landing pages
--------------------

To customize a blog page, go to :menuselection:`Edit --> Style` and use the available options as
desired:

- :guilabel:`Top Banner`: displays the title of the page.
- :guilabel:`Full width`: displays the banner widely.
- :guilabel:`Layout`:  displays blog posts as grid or as list.
- :guilabel:`Cards`: displays blog posts with a *card* effect.
- :guilabel:`Increase Readability`: Enhances text appearance for better reading comfort without
  changing the content.
- :guilabel:`Sidebar`: displays archives, social networks and :ref:`tags list <blog/tags>`.
- :guilabel:`Archives`: enables filtering posts by selected month.
- :guilabel:`Follow Us`: displays links to social networks. To add or customize a social network,
   click the :guilabel:`Follow us` block, click :guilabel:`Add New Social Network` and copy/paste
   your account URL next to the network field. Toggle the switch button on or off to enable or
   disable a social network.
- :guilabel:`Tags List`: displays the list of :ref:`tags <blog/tags>` for filtering purposes.
- :guilabel:`Posts List`: displays the posts' covers or hides them.
- :guilabel:`Author`: displays the posts' authors.
- :guilabel:`Comments/Views Stats`: displays the posts' number of comments and views.
- :guilabel:`Teaser & Tags`: displays the posts' first sentences and tags.

.. tip::

   To change the cover's background, click the blog post and edit the :guilabel:`Background`
   field in the :guilabel:`Cover` section.

After applying the desired changes, click :guilabel:`Save`

.. note::
   Settings apply to **all** blogs pages.
.. Note::
   Increase blogs' visibility in search engines, attract more visitors and more clicks while
   improving the :doc:`SEO <../../../applications/websites/website/structure/seo>` by:

   - Updating the content of the website regularly.
   - Using meta tags and ensure both the website content and its metadata are translated.
   - Never having more than one :ref:`Heading 1 <website/elements/titles>` per page so the
     :doc:`SEO <../../../applications/websites/website/structure/seo>` can easily identify the
     main topic of the page.
   - Use the :guilabel:`Blog` :ref:`building blocks <website/building_blocks/add>` anywhere on the
     website to increase the blog's visibility.