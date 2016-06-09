
The purpose of these files is to convert the raw open data policy text to a format that the State Decoded software can parse into it's database. 

These may also be able to be converted to other formats for future use. 

Below is the XML code to append (before and after) the raw text. script or person must fill out the strcuture, section numbe, 

<!-- PUT JURISDICTION NAME HERE, (city, state, etc)  Ex. Las Vegas, NV -->
<!-- StateDecoded XML Examples
http://docs.statedecoded.com/xml-format.html-->

<?xml version="1.0" encoding="utf-8"?>
<law>
    <structure>
        <unit label="section" identifier="amherstny2014" level="1"></unit>
    </structure>
    <section_number>"amherstny2014</section_number> <!--citystateyear, no spaces-->
    <catch_line>Amherst, NY (2014)</catch_line>
    <text>
<!--insert text of the policy below this line !-->

<history>
    <!-- put resolution/executive order law history in this area. (Adopted on, council votes, date passed etc) --> 
Passed on 10/06/2014. Resolution 2014-1055
</history>
    <!--<metadata></metadata>-->
    <tags>
        <!-- Tag if this juristiction is a city state, etc --> 
        <tag>city</tag>
        <!-- <tag>state</tag> --> 
        <!-- <tag>county</tag> -->
        <!-- <tag>executive order</tag> --> 
        <tag>resolution</tag>
    </tags>
    </text>
</law>