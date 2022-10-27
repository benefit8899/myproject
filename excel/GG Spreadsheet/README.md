# myproject
Fomular
  1. Query: https://support.google.com/docs/answer/3093343?hl=en
    - QUERY(A2:E6,"select avg(A) pivot B")
    - Query IN and compare with date
      QUERY(Ticket!$A$2:$T$199,"SELECT COUNT(B) WHERE R >= date '"&TEXT($O$3,"yyyy-mm-dd")&"' AND (E = '" & TEXTJOIN("' OR E = '",true, $B$32:$B$36)&"') label count(B)''")
