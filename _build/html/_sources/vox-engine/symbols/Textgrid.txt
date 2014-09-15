

===============================================
Textgrid (data)
===============================================
METHODS FOR IMPLEMENTING TEXTGRIDS

.. contents::
   :local:

.. js:data:: Textgrid

      
   
   .. ============================== constructor details ====================
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   .. ============================== properties summary =====================
   
   
   
   .. ============================== events summary ========================
   
   
   
   
   
   .. ============================== field details ==========================
   
   
   
   .. ============================== method details =========================
   
   
   
   
   
   
   .. js:function:: Textgrid.rowList()
   
       
   
       
   
       Returns the GRID-row list
   
       
       
   
       .. code-block:: javascript
   
                        var listRow;
                        listRow = inputs('Q').rowList();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list
   
       :rtype: list
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.columnList()
   
       
   
       
   
       Returns the GRID-column list
   
       
       
   
       .. code-block:: javascript
   
                        var listColumn;
                        listColumn = inputs('Q').columnList();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list
   
       :rtype: list
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.assignRowList(list)
   
       
   
       
       
       :param list list:
   
         to be assigned
   
         
       
       
   
       Assigns a list to the GRID-row
   
       
       
   
       .. code-block:: javascript
   
                        var newRowlist;
                        inputs('Q').assignRowList(newRowlist);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.assignColumnList(list)
   
       
   
       
       
       :param list list:
   
         to be assigned
   
         
       
       
   
       Assigns a list to the GRID-column
   
       
       
   
       .. code-block:: javascript
   
                        var newColumnlist;
                        inputs('Q').assignColumnList(newColumnlist);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.textForRowColumn(row-label, column-label)
   
       
   
       
       
       :param string row-label:
   
         
   
         
       
       :param string column-label:
   
         
   
         
       
       
   
       Returns the value of the cell defined by (rowLabel, columnLabel)
   
       
       
   
       .. code-block:: javascript
   
                        var text;
                        text = inputs('Q').textForRowColumn('1','1');
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         
   
       :rtype: string
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.setTextForRowColumn(value, row-label, column-label)
   
       
   
       
       
       :param  value:
   
         
   
         
       
       :param string row-label:
   
         
   
         
       
       :param string column-label:
   
         
   
         
       
       
   
       Sets the value of the cell defined by (rowLabel, columnLabel)
   
       
       
   
       .. code-block:: javascript
   
                        var text = 'Some text';
                        inputs('Q').setTextForRowColumn(text);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.pipeRow(list)
   
       
   
       
       
       :param list list:
   
         to be piped
   
         
       
       
   
       Pipes a list to the GRID-row replacing any pre-assigned list
   
       
       
   
       .. code-block:: javascript
   
                        var newList;
                        inputs('Q').pipeRow(newList);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Textgrid.pipeColumn(list)
   
       
   
       
       
       :param list list:
   
         to be piped
   
         
       
       
   
       Pipes a list to the GRID-column replacing any pre-assigned list
   
       
       
   
       .. code-block:: javascript
   
                        var newList;
                        inputs('Q').pipeColumn(newList);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   .. ============================== event details =========================
   
   

.. container:: footer

   Documentation generated by jsdoc-toolkit_  2.4.0 using jsdoc-toolkit-rst-template_

.. _jsdoc-toolkit: http://code.google.com/p/jsdoc-toolkit/
.. _jsdoc-toolkit-rst-template: http://code.google.com/p/jsdoc-toolkit-rst-template/
.. _sphinx: http://sphinx.pocoo.org/




.. vim: set ft=rst :
