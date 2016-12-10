# ARROWC
=========
ARROWC
=======

ARROWC  is  used  only  in  America.which  is  invented  by wilmix jemin j in  web p.l at year  2016.


ARROWC consists of  3  modules  that  are   used  with  webpart1, webpart2, webpart3.



ADVANTAGES:
===========

It behave  like  web.


SYNTAX:
=======


<ARROWC>
<IMPORT> 
<PACK> MyP
{
    <CLASS> Programs
    {
          public void main()
        {
		
	<! ARROWC LOGIC>


}

}
}


Program-1:
==========

<ARROWC>
<USE> WDBA;
<USE> CDollar.WDBA;
<IMPORT> 
<PACK> MyP
{
    <CLASS> Programs
    {
          public void main()
        {
		
	LArray root <NEW> LArray("root");
		
	
		
		
		
		root.add("wilmix");
		root.add("jemin");
		root.add("shalom");
		root.add("1010");
		root.add("101");
		root.add("201");
		
		root.add("100000000");
		//print the tree's size and contents
		
		root.printTree();


<TRY>
{

    string g = WDBASQL.WDBASQLS("datastores", "USEDATABASE", "dbpwds", "C:\\Programs\\WNOSQL\\WNOSQLProgramfiles\\WNOSQL-cod");




    string t = WDBASQL.WDBASQLS("dbuser", "dbpwds", 1, "wilmix78", "wilmix78", 1, 5, g);


    string s1 = "SelectAll from Telecom 3 to 29 , 1 to 7 ?= C By 1 1 : {0} : {0} :{0}";



    java.util.ArrayList ar = WDBALIB.WDBAQUERY(s1, t);


<PRINTLN>(""+ar);




}

<CATCH> (<EXE> e) { }


		
}


}

}

