

===============================================
INPUTS (data)
===============================================
<tt>METHODS COMMON TO ALL INPUT TYPES<tt>

.. contents::
   :local:

.. js:data:: INPUTS

      
   
   .. ============================== constructor details ====================
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   .. ============================== properties summary =====================
   
   
   
   .. ============================== events summary ========================
   
   
   
   
   
   .. ============================== field details ==========================
   
   
   
   .. ============================== method details =========================
   
   
   
   
   
   
   .. js:function:: INPUTS.label()
   
       
   
       
   
       Returns the label of an input type
   
       
       
   
       .. code-block:: javascript
   
                          var Qlabel;
                          Qlabel = inputs('Q').label();
                          //This will give the 'Label' of the input 'Q'
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         label
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.id()
   
       
   
       
   
       Returns the id of an input type
   
       
       
   
       .. code-block:: javascript
   
                          var Qid;
                          Qid = inputs('Q').id();
                          //This will give the ID of the input 'Q'
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         id
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.hidden(bool)
   
       
   
       
       
       :param boolean bool:
   
         true/false
   
         
       
       
   
       Controls the visibility of the question
   
       
       
   
       .. code-block:: javascript
   
                          inputs('Q').hidden(true); // Input type 'Q' hidden
                          inputs('Q').hidden(false); // Input type 'Q' not hidden
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.disable(bool)
   
       
   
       
       
       :param boolean bool:
   
         true/false
   
         
       
       
   
       Control the disability of the question
   
       
       
   
       .. code-block:: javascript
   
                          inputs('Q').disabled(true); // Input type 'Q' disabled
                          inputs('Q').disabled(false); // Input type 'Q' not disabled
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.isSelected(Item)
   
       
   
       
       
       :param string Item:
   
         label
   
         
       
       
   
       To check whether item is selected or not
   
       
       
   
       .. code-block:: javascript
   
                        if(inputs('Q').isSelected('2'))
                        {
                              //Do something
                        }
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         bool true/false
   
       :rtype: boolean
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.selectedCount()
   
       
   
       
   
       Gives the count of selected items
   
       
       
   
       .. code-block:: javascript
   
                        var count;
                        count = inputs('Q').selectedCount();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         count
   
       :rtype: number
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.unselectedCount()
   
       
   
       
   
       Gives the count of unselected items
   
       
       
   
       .. code-block:: javascript
   
                        var count;
                        count = inputs('Q').unselectedCount();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         count
   
       :rtype: number
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.selected()
   
       
   
       
   
       To get selected items
   
       
       
   
       .. code-block:: javascript
   
          
                       var selected = inputs('Q').selected();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list List of selected items
   
       :rtype: list
       
     
   
     
   
     
   
   
   
   
   .. js:function:: INPUTS.unselected()
   
       
   
       
   
       To get items not selected
   
       
       
   
       .. code-block:: javascript
   
          
                       var unselected = inputs('Q').unselected();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list List of unselected items
   
       :rtype: list
       
     
   
     
   
     
   
   
   
   .. ============================== event details =========================
   
   

.. container:: footer

   Documentation generated by jsdoc-toolkit_  2.4.0 using jsdoc-toolkit-rst-template_

.. _jsdoc-toolkit: http://code.google.com/p/jsdoc-toolkit/
.. _jsdoc-toolkit-rst-template: http://code.google.com/p/jsdoc-toolkit-rst-template/
.. _sphinx: http://sphinx.pocoo.org/




.. vim: set ft=rst :
