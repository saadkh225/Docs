

===============================================
Choicegrid (data)
===============================================
METHODS FOR IMPLEMENTING CHOICEGRIDS

.. contents::
   :local:

.. js:data:: Choicegrid

      
   
   .. ============================== constructor details ====================
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   .. ============================== properties summary =====================
   
   
   
   .. ============================== events summary ========================
   
   
   
   
   
   .. ============================== field details ==========================
   
   
   
   .. ============================== method details =========================
   
   
   
   
   
   
   .. js:function:: Choicegrid.rowList()
   
       
   
       
   
       Returns the GRID-row list
   
       
       
   
       .. code-block:: javascript
   
          
                        var listRow;
                        listRow = inputs('Q').rowList();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.colummnList()
   
       
   
       
   
       Returns the GRID-column list
   
       
       
   
       .. code-block:: javascript
   
                        var listColumn;
                        listColumn = inputs('Q').columnList();
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.assignRowList(list)
   
       
   
       
       
       :param  list:
   
         
   
         
       
       
   
       Assigns a list to GRID-row replacing the current row-list if there is one assigned
   
       
       
   
       .. code-block:: javascript
   
                        var newRowlist;
                        inputs('Q').assignRowList(newRowlist);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.assignColumnList(list)
   
       
   
       
       
       :param  list:
   
         
   
         
       
       
   
       Assigns a list to GRID-column replacing the current column-list if there is one assigned
   
       
       
   
       .. code-block:: javascript
   
                        var newColumnlist;
                        inputs('Q').assignColumnList(newColumnlist);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.isSelected(rowLabel, columnLabel)
   
       
   
       
       
       :param string rowLabel:
   
         
   
         
       
       :param string columnLabel:
   
         
   
         
       
       
   
       Tells whether a particular cell defined by (rowLabel, columnLabel) is selected or not
   
       
       
   
       .. code-block:: javascript
   
                        if(inputs('Q').isSelected(('1'),('2')))
                        { 
                              console.log('Cell (1,2) is selected');
                        }
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         Boolean true/false
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.pipeRow(list)
   
       
   
       
       
       :param  list:
   
         
   
         
       
       
   
       Assigns a list to GRID-row replacing any pre-assigned list
   
       
       
   
       .. code-block:: javascript
   
          
                        var newList;
                        inputs('Q').pipeRow(newList);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.pipeColumn(list)
   
       
   
       
       
       :param  list:
   
         
   
         
       
       
   
       Assigns a list to GRID-column replacing any pre-assigned list
   
       
       
   
       .. code-block:: javascript
   
                        var newList;
                        inputs('Q').pipeColumn(newList);
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         none
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.selectedColumnsForRows(rowLabel)
   
       
   
       
       
       :param  rowLabel:
   
         
   
         
       
       
   
       Returns a list of items selected in the particular row (rowLabels)
   
       
       
   
       .. code-block:: javascript
   
                        var selecteditems;
                        selecteditems = inputs('Q1').selectedColumnsForRows('Row_1');
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list
   
       
       
     
   
     
   
     
   
   
   
   
   .. js:function:: Choicegrid.selectedRowsForColumns(columnLabel)
   
       
   
       
       
       :param  columnLabel:
   
         
   
         
       
       
   
       Returns a list of items selected in the particular column (rowLabels)
       
       A method of {@link METHODS FOR IMPLEMENTING CHOICEGRIDS}
   
       
       
   
       .. code-block:: javascript
   
                        var selecteditems;
                        selecteditems = inputs('Q1').selectedRowsForColumns('column_1');
   
       
       
   
   
     
   
     
   
     
   
     
       
       :returns:
         list
   
       
       
     
   
     
   
     
   
   
   
   .. ============================== event details =========================
   
   

.. container:: footer

   Documentation generated by jsdoc-toolkit_  2.4.0 using jsdoc-toolkit-rst-template_

.. _jsdoc-toolkit: http://code.google.com/p/jsdoc-toolkit/
.. _jsdoc-toolkit-rst-template: http://code.google.com/p/jsdoc-toolkit-rst-template/
.. _sphinx: http://sphinx.pocoo.org/




.. vim: set ft=rst :
