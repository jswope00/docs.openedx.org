==============================
Adding Tooltips to a Problem
==============================

To help learners understand terminology or other aspects of a problem, you can
add inline tooltips. Tooltips show text to learners when they move their
cursors over a tooltip icon.

The following example problem includes two tooltips. The tooltip that provides
a definition for "ROI" is being shown.

.. image:: ../images/tooltip.png
 :alt: An example of a tooltip from a learner's point of view.
 :width: 500

.. note::
  For learners using a screen reader, the tooltip expands to make its
  associated text accessible when the screen reader focuses on the tooltip
  icon.

To add the tooltip, you wrap the text that you want to appear as the tooltip in
the ``clarification`` element.  For example, the following problem contains two
tooltips.

.. code-block:: xml

  <problem>
      <text>
          <p>Given the data in Table 7 <clarification>Table 7: "Example PV
            Installation Costs", Page 171 of Roberts textbook</clarification>,
            compute the ROI <clarification><strong>ROI</strong>: Return on
            Investment</clarification> over 20 years.
          </p>
       . . .
..
  _Start Task List
.. task-list::
    :custom:

    1. [ ] Links Verified
    2. [ ] References to edX/2U/edx.org removed or changed to Open edX® LMS
    3. [ ] Tagged with taxonomy term
..
  _End Task List
