# myproject
Fomular
  1. Query: https://support.google.com/docs/answer/3093343?hl=en
  2. 
    - QUERY(A2:E6,"select avg(A) pivot B")
    - 
    - Query IN and compare with date
        - QUERY(Ticket!$A$2:$T$199,"SELECT COUNT(B) WHERE R >= date '"&TEXT($O$3,"yyyy-mm-dd")&"' AND (E = '" & TEXTJOIN("' OR E = '",true, $B$32:$B$36)&"') label count(B)''")
    - PIVOT: TRANSPOSE
    - Combine Rang: query({A33:A38; B33:B38; C33:C38}, "SELECT * ORDER BY Col1")
