-----------------------------------

###Planning for pyramid interactive browsable tables.

Turning back to jQuery, again, if this time I could make it work..

[https://forum.jquery.com/topic/run-jquery-code-without-a-web-server](https://forum.jquery.com/topic/run-jquery-code-without-a-web-server])

--------------------------------

How to run jquery on local machine
[https://www.codecademy.com/en/forum_questions/51205802e1738f7cce000002](https://www.codecademy.com/en/forum_questions/51205802e1738f7cce000002)

From above page

###How to run jquery on local machine

So i figured this out. 
You have to tell the webpage that you want to use jQuery and where it should get it. 
You can either put the latest jQuery file in on your server or link to it. 

**Here is how i did it:**

<script type="text/javascript" src="jquery-1.9.1.min.js"></script>
<script type="text/javascript" src="script.js"></script>
I simply downloaded jQuery from http://jquery.com/download/ 
Simply edit this so your path to the file is correct, and it should work :) Mine did!

It also works directly from the web by putting the link, like so:

<script type="text/javascript" src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
<script type="text/javascript" src="script.js"></script>
Hope it helps.

----------------------------------

OK, now. 

let's see what can I test this with.

-----------------------------------

```html

  <script type="text/javascript" src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
  <script type="text/javascript" src="script.js"></script>

```

------------------------------------

https://www.sitepoint.com/12-amazing-jquery-tables/

-------------------------------------

https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js
https://cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css

--------------------------------------

OK, so how do I include these ?

view-source:https://datatables.net/

--------------------------------------------

<div class="cdn">
    <span>CSS</span>
    <input type="text" value="//cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css" readonly>
</div>

<div class="cdn">
    <span>JS</span>
    <input type="text" value="//cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js" readonly>
</div>

<p>An example of DataTables in action is shown below.</p></div></div>

<p><table id="example" class="display" cellspacing="0" width="100%"><thead><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></thead><tfoot><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></tfoot><tbody><tr><td>Tiger Nixon</td><td>System Architect</td><td>Edinburgh</td><td>61</td><td>2011/04/25</td><td>$320,800</td></tr><tr><td>Garrett Winters</td><td>Accountant</td><td>Tokyo</td><td>63</td><td>2011/07/25</td><td>$170,750</td></tr><tr><td>Ashton Cox</td><td>Junior Technical Author</td><td>San Francisco</td><td>66</td><td>2009/01/12</td><td>$86,000</td></tr><tr><td>Cedric Kelly</td><td>Senior Javascript Developer</td><td>Edinburgh</td><td>22</td><td>2012/03/29</td><td>$433,060</td></tr><tr><td>Airi Satou</td><td>Accountant</td><td>Tokyo</td><td>33</td><td>2008/11/28</td><td>$162,700</td></tr><tr><td>Brielle Williamson</td><td>Integration Specialist</td><td>New York</td><td>61</td><td>2012/12/02</td><td>$372,000</td></tr><tr><td>Herrod Chandler</td><td>Sales Assistant</td><td>San Francisco</td><td>59</td><td>2012/08/06</td><td>$137,500</td></tr><tr><td>Rhona Davidson</td><td>Integration Specialist</td><td>Tokyo</td><td>55</td><td>2010/10/14</td><td>$327,900</td></tr><tr><td>Colleen Hurst</td><td>Javascript Developer</td><td>San Francisco</td><td>39</td><td>2009/09/15</td><td>$205,500</td></tr><tr><td>Sonya Frost</td><td>Software Engineer</td><td>Edinburgh</td><td>23</td><td>2008/12/13</td><td>$103,600</td></tr><tr><td>Jena Gaines</td><td>Office Manager</td><td>London</td><td>30</td><td>2008/12/19</td><td>$90,560</td></tr><tr><td>Quinn Flynn</td><td>Support Lead</td><td>Edinburgh</td><td>22</td><td>2013/03/03</td><td>$342,000</td></tr><tr><td>Charde Marshall</td><td>Regional Director</td><td>San Francisco</td><td>36</td><td>2008/10/16</td><td>$470,600</td></tr><tr><td>Haley Kennedy</td><td>Senior Marketing Designer</td><td>London</td><td>43</td><td>2012/12/18</td><td>$313,500</td></tr><tr><td>Tatyana Fitzpatrick</td><td>Regional Director</td><td>London</td><td>19</td><td>2010/03/17</td><td>$385,750</td></tr><tr><td>Michael Silva</td><td>Marketing Designer</td><td>London</td><td>66</td><td>2012/11/27</td><td>$198,500</td></tr><tr><td>Paul Byrd</td><td>Chief Financial Officer (CFO)</td><td>New York</td><td>64</td><td>2010/06/09</td><td>$725,000</td></tr><tr><td>Gloria Little</td><td>Systems Administrator</td><td>New York</td><td>59</td><td>2009/04/10</td><td>$237,500</td></tr><tr><td>Bradley Greer</td><td>Software Engineer</td><td>London</td><td>41</td><td>2012/10/13</td><td>$132,000</td></tr><tr><td>Dai Rios</td><td>Personnel Lead</td><td>Edinburgh</td><td>35</td><td>2012/09/26</td><td>$217,500</td></tr><tr><td>Jenette Caldwell</td><td>Development Lead</td><td>New York</td><td>30</td><td>2011/09/03</td><td>$345,000</td></tr><tr><td>Yuri Berry</td><td>Chief Marketing Officer (CMO)</td><td>New York</td><td>40</td><td>2009/06/25</td><td>$675,000</td></tr><tr><td>Caesar Vance</td><td>Pre-Sales Support</td><td>New York</td><td>21</td><td>2011/12/12</td><td>$106,450</td></tr><tr><td>Doris Wilder</td><td>Sales Assistant</td><td>Sidney</td><td>23</td><td>2010/09/20</td><td>$85,600</td></tr><tr><td>Angelica Ramos</td><td>Chief Executive Officer (CEO)</td><td>London</td><td>47</td><td>2009/10/09</td><td>$1,200,000</td></tr><tr><td>Gavin Joyce</td><td>Developer</td><td>Edinburgh</td><td>42</td><td>2010/12/22</td><td>$92,575</td></tr><tr><td>Jennifer Chang</td><td>Regional Director</td><td>Singapore</td><td>28</td><td>2010/11/14</td><td>$357,650</td></tr><tr><td>Brenden Wagner</td><td>Software Engineer</td><td>San Francisco</td><td>28</td><td>2011/06/07</td><td>$206,850</td></tr><tr><td>Fiona Green</td><td>Chief Operating Officer (COO)</td><td>San Francisco</td><td>48</td><td>2010/03/11</td><td>$850,000</td></tr><tr><td>Shou Itou</td><td>Regional Marketing</td><td>Tokyo</td><td>20</td><td>2011/08/14</td><td>$163,000</td></tr><tr><td>Michelle House</td><td>Integration Specialist</td><td>Sidney</td><td>37</td><td>2011/06/02</td><td>$95,400</td></tr><tr><td>Suki Burks</td><td>Developer</td><td>London</td><td>53</td><td>2009/10/22</td><td>$114,500</td></tr><tr><td>Prescott Bartlett</td><td>Technical Author</td><td>London</td><td>27</td><td>2011/05/07</td><td>$145,000</td></tr><tr><td>Gavin Cortez</td><td>Team Leader</td><td>San Francisco</td><td>22</td><td>2008/10/26</td><td>$235,500</td></tr><tr><td>Martena Mccray</td><td>Post-Sales support</td><td>Edinburgh</td><td>46</td><td>2011/03/09</td><td>$324,050</td></tr><tr><td>Unity Butler</td><td>Marketing Designer</td><td>San Francisco</td><td>47</td><td>2009/12/09</td><td>$85,675</td></tr><tr><td>Howard Hatfield</td><td>Office Manager</td><td>San Francisco</td><td>51</td><td>2008/12/16</td><td>$164,500</td></tr><tr><td>Hope Fuentes</td><td>Secretary</td><td>San Francisco</td><td>41</td><td>2010/02/12</td><td>$109,850</td></tr><tr><td>Vivian Harrell</td><td>Financial Controller</td><td>San Francisco</td><td>62</td><td>2009/02/14</td><td>$452,500</td></tr><tr><td>Timothy Mooney</td><td>Office Manager</td><td>London</td><td>37</td><td>2008/12/11</td><td>$136,200</td></tr><tr><td>Jackson Bradshaw</td><td>Director</td><td>New York</td><td>65</td><td>2008/09/26</td><td>$645,750</td></tr><tr><td>Olivia Liang</td><td>Support Engineer</td><td>Singapore</td><td>64</td><td>2011/02/03</td><td>$234,500</td></tr><tr><td>Bruno Nash</td><td>Software Engineer</td><td>London</td><td>38</td><td>2011/05/03</td><td>$163,500</td></tr><tr><td>Sakura Yamamoto</td><td>Support Engineer</td><td>Tokyo</td><td>37</td><td>2009/08/19</td><td>$139,575</td></tr><tr><td>Thor Walton</td><td>Developer</td><td>New York</td><td>61</td><td>2013/08/11</td><td>$98,540</td></tr><tr><td>Finn Camacho</td><td>Support Engineer</td><td>San Francisco</td><td>47</td><td>2009/07/07</td><td>$87,500</td></tr><tr><td>Serge Baldwin</td><td>Data Coordinator</td><td>Singapore</td><td>64</td><td>2012/04/09</td><td>$138,575</td></tr><tr><td>Zenaida Frank</td><td>Software Engineer</td><td>New York</td><td>63</td><td>2010/01/04</td><td>$125,250</td></tr><tr><td>Zorita Serrano</td><td>Software Engineer</td><td>San Francisco</td><td>56</td><td>2012/06/01</td><td>$115,000</td></tr><tr><td>Jennifer Acosta</td><td>Junior Javascript Developer</td><td>Edinburgh</td><td>43</td><td>2013/02/01</td><td>$75,650</td></tr><tr><td>Cara Stevens</td><td>Sales Assistant</td><td>New York</td><td>46</td><td>2011/12/06</td><td>$145,600</td></tr><tr><td>Hermione Butler</td><td>Regional Director</td><td>London</td><td>47</td><td>2011/03/21</td><td>$356,250</td></tr><tr><td>Lael Greer</td><td>Systems Administrator</td><td>London</td><td>21</td><td>2009/02/27</td><td>$103,500</td></tr><tr><td>Jonas Alexander</td><td>Developer</td><td>San Francisco</td><td>30</td><td>2010/07/14</td><td>$86,500</td></tr><tr><td>Shad Decker</td><td>Regional Director</td><td>Edinburgh</td><td>51</td><td>2008/11/13</td><td>$183,000</td></tr><tr><td>Michael Bruce</td><td>Javascript Developer</td><td>Singapore</td><td>29</td><td>2011/06/27</td><td>$183,000</td></tr><tr><td>Donna Snider</td><td>Customer Support</td><td>New York</td><td>27</td><td>2011/01/25</td><td>$112,000</td></tr></tbody></table></p>


------------------------------------------

So, this should do it :

-------------------------------------------

<HTML>
<head>

<meta http-equiv="expires"
content=0
/>

<div class="cdn">
    <span>CSS</span>
    <input type="text" value="//cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css" readonly>
</div>

<div class="cdn">
    <span>JS</span>
    <input type="text" value="//cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js" readonly>
</div>

</head>


<body>

<p>An example of DataTables in action is shown below.</p></div></div>

<p><table id="example" class="display" cellspacing="0" width="100%"><thead><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></thead><tfoot><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></tfoot><tbody><tr><td>Tiger Nixon</td><td>System Architect</td><td>Edinburgh</td><td>61</td><td>2011/04/25</td><td>$320,800</td></tr><tr><td>Garrett Winters</td><td>Accountant</td><td>Tokyo</td><td>63</td><td>2011/07/25</td><td>$170,750</td></tr><tr><td>Ashton Cox</td><td>Junior Technical Author</td><td>San Francisco</td><td>66</td><td>2009/01/12</td><td>$86,000</td></tr><tr><td>Cedric Kelly</td><td>Senior Javascript Developer</td><td>Edinburgh</td><td>22</td><td>2012/03/29</td><td>$433,060</td></tr><tr><td>Airi Satou</td><td>Accountant</td><td>Tokyo</td><td>33</td><td>2008/11/28</td><td>$162,700</td></tr><tr><td>Brielle Williamson</td><td>Integration Specialist</td><td>New York</td><td>61</td><td>2012/12/02</td><td>$372,000</td></tr><tr><td>Herrod Chandler</td><td>Sales Assistant</td><td>San Francisco</td><td>59</td><td>2012/08/06</td><td>$137,500</td></tr><tr><td>Rhona Davidson</td><td>Integration Specialist</td><td>Tokyo</td><td>55</td><td>2010/10/14</td><td>$327,900</td></tr><tr><td>Colleen Hurst</td><td>Javascript Developer</td><td>San Francisco</td><td>39</td><td>2009/09/15</td><td>$205,500</td></tr><tr><td>Sonya Frost</td><td>Software Engineer</td><td>Edinburgh</td><td>23</td><td>2008/12/13</td><td>$103,600</td></tr><tr><td>Jena Gaines</td><td>Office Manager</td><td>London</td><td>30</td><td>2008/12/19</td><td>$90,560</td></tr><tr><td>Quinn Flynn</td><td>Support Lead</td><td>Edinburgh</td><td>22</td><td>2013/03/03</td><td>$342,000</td></tr><tr><td>Charde Marshall</td><td>Regional Director</td><td>San Francisco</td><td>36</td><td>2008/10/16</td><td>$470,600</td></tr><tr><td>Haley Kennedy</td><td>Senior Marketing Designer</td><td>London</td><td>43</td><td>2012/12/18</td><td>$313,500</td></tr><tr><td>Tatyana Fitzpatrick</td><td>Regional Director</td><td>London</td><td>19</td><td>2010/03/17</td><td>$385,750</td></tr><tr><td>Michael Silva</td><td>Marketing Designer</td><td>London</td><td>66</td><td>2012/11/27</td><td>$198,500</td></tr><tr><td>Paul Byrd</td><td>Chief Financial Officer (CFO)</td><td>New York</td><td>64</td><td>2010/06/09</td><td>$725,000</td></tr><tr><td>Gloria Little</td><td>Systems Administrator</td><td>New York</td><td>59</td><td>2009/04/10</td><td>$237,500</td></tr><tr><td>Bradley Greer</td><td>Software Engineer</td><td>London</td><td>41</td><td>2012/10/13</td><td>$132,000</td></tr><tr><td>Dai Rios</td><td>Personnel Lead</td><td>Edinburgh</td><td>35</td><td>2012/09/26</td><td>$217,500</td></tr><tr><td>Jenette Caldwell</td><td>Development Lead</td><td>New York</td><td>30</td><td>2011/09/03</td><td>$345,000</td></tr><tr><td>Yuri Berry</td><td>Chief Marketing Officer (CMO)</td><td>New York</td><td>40</td><td>2009/06/25</td><td>$675,000</td></tr><tr><td>Caesar Vance</td><td>Pre-Sales Support</td><td>New York</td><td>21</td><td>2011/12/12</td><td>$106,450</td></tr><tr><td>Doris Wilder</td><td>Sales Assistant</td><td>Sidney</td><td>23</td><td>2010/09/20</td><td>$85,600</td></tr><tr><td>Angelica Ramos</td><td>Chief Executive Officer (CEO)</td><td>London</td><td>47</td><td>2009/10/09</td><td>$1,200,000</td></tr><tr><td>Gavin Joyce</td><td>Developer</td><td>Edinburgh</td><td>42</td><td>2010/12/22</td><td>$92,575</td></tr><tr><td>Jennifer Chang</td><td>Regional Director</td><td>Singapore</td><td>28</td><td>2010/11/14</td><td>$357,650</td></tr><tr><td>Brenden Wagner</td><td>Software Engineer</td><td>San Francisco</td><td>28</td><td>2011/06/07</td><td>$206,850</td></tr><tr><td>Fiona Green</td><td>Chief Operating Officer (COO)</td><td>San Francisco</td><td>48</td><td>2010/03/11</td><td>$850,000</td></tr><tr><td>Shou Itou</td><td>Regional Marketing</td><td>Tokyo</td><td>20</td><td>2011/08/14</td><td>$163,000</td></tr><tr><td>Michelle House</td><td>Integration Specialist</td><td>Sidney</td><td>37</td><td>2011/06/02</td><td>$95,400</td></tr><tr><td>Suki Burks</td><td>Developer</td><td>London</td><td>53</td><td>2009/10/22</td><td>$114,500</td></tr><tr><td>Prescott Bartlett</td><td>Technical Author</td><td>London</td><td>27</td><td>2011/05/07</td><td>$145,000</td></tr><tr><td>Gavin Cortez</td><td>Team Leader</td><td>San Francisco</td><td>22</td><td>2008/10/26</td><td>$235,500</td></tr><tr><td>Martena Mccray</td><td>Post-Sales support</td><td>Edinburgh</td><td>46</td><td>2011/03/09</td><td>$324,050</td></tr><tr><td>Unity Butler</td><td>Marketing Designer</td><td>San Francisco</td><td>47</td><td>2009/12/09</td><td>$85,675</td></tr><tr><td>Howard Hatfield</td><td>Office Manager</td><td>San Francisco</td><td>51</td><td>2008/12/16</td><td>$164,500</td></tr><tr><td>Hope Fuentes</td><td>Secretary</td><td>San Francisco</td><td>41</td><td>2010/02/12</td><td>$109,850</td></tr><tr><td>Vivian Harrell</td><td>Financial Controller</td><td>San Francisco</td><td>62</td><td>2009/02/14</td><td>$452,500</td></tr><tr><td>Timothy Mooney</td><td>Office Manager</td><td>London</td><td>37</td><td>2008/12/11</td><td>$136,200</td></tr><tr><td>Jackson Bradshaw</td><td>Director</td><td>New York</td><td>65</td><td>2008/09/26</td><td>$645,750</td></tr><tr><td>Olivia Liang</td><td>Support Engineer</td><td>Singapore</td><td>64</td><td>2011/02/03</td><td>$234,500</td></tr><tr><td>Bruno Nash</td><td>Software Engineer</td><td>London</td><td>38</td><td>2011/05/03</td><td>$163,500</td></tr><tr><td>Sakura Yamamoto</td><td>Support Engineer</td><td>Tokyo</td><td>37</td><td>2009/08/19</td><td>$139,575</td></tr><tr><td>Thor Walton</td><td>Developer</td><td>New York</td><td>61</td><td>2013/08/11</td><td>$98,540</td></tr><tr><td>Finn Camacho</td><td>Support Engineer</td><td>San Francisco</td><td>47</td><td>2009/07/07</td><td>$87,500</td></tr><tr><td>Serge Baldwin</td><td>Data Coordinator</td><td>Singapore</td><td>64</td><td>2012/04/09</td><td>$138,575</td></tr><tr><td>Zenaida Frank</td><td>Software Engineer</td><td>New York</td><td>63</td><td>2010/01/04</td><td>$125,250</td></tr><tr><td>Zorita Serrano</td><td>Software Engineer</td><td>San Francisco</td><td>56</td><td>2012/06/01</td><td>$115,000</td></tr><tr><td>Jennifer Acosta</td><td>Junior Javascript Developer</td><td>Edinburgh</td><td>43</td><td>2013/02/01</td><td>$75,650</td></tr><tr><td>Cara Stevens</td><td>Sales Assistant</td><td>New York</td><td>46</td><td>2011/12/06</td><td>$145,600</td></tr><tr><td>Hermione Butler</td><td>Regional Director</td><td>London</td><td>47</td><td>2011/03/21</td><td>$356,250</td></tr><tr><td>Lael Greer</td><td>Systems Administrator</td><td>London</td><td>21</td><td>2009/02/27</td><td>$103,500</td></tr><tr><td>Jonas Alexander</td><td>Developer</td><td>San Francisco</td><td>30</td><td>2010/07/14</td><td>$86,500</td></tr><tr><td>Shad Decker</td><td>Regional Director</td><td>Edinburgh</td><td>51</td><td>2008/11/13</td><td>$183,000</td></tr><tr><td>Michael Bruce</td><td>Javascript Developer</td><td>Singapore</td><td>29</td><td>2011/06/27</td><td>$183,000</td></tr><tr><td>Donna Snider</td><td>Customer Support</td><td>New York</td><td>27</td><td>2011/01/25</td><td>$112,000</td></tr></tbody></table></p>


</body>
</HTML>

-----------------------------------------------

Shows as a table.
Does not show anything fancy.

Let's fix ..

----------------------------------------------

<div class="cdn">
    <span>CSS</span>
    <input type="text" value="https://cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css" readonly>
</div>

<div class="cdn">
    <span>JS</span>
    <input type="text" value="https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js" readonly>
</div>

----------------------------------------------


<HTML>
<head>

<meta http-equiv="expires"
content=0
/>


		<script type="text/javascript" language="javascript" src="//cdn.datatables.net/responsive/1.0.0/js/dataTables.responsive.min.js"></script>

		<script type="text/javascript">

		$(document).ready( function () {
			$('#example')
				.addClass( 'nowrap' )
				.dataTable( {
					responsive: true,
					columnDefs: [
						{ targets: [-1, -3], className: 'dt-body-right' }
					]
				} );


		</script>

</head>


<body>

<p>An example of DataTables in action is shown below.</p></div></div>

<p><table id="example" class="display" cellspacing="0" width="100%"><thead><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></thead><tfoot><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></tfoot><tbody><tr><td>Tiger Nixon</td><td>System Architect</td><td>Edinburgh</td><td>61</td><td>2011/04/25</td><td>$320,800</td></tr><tr><td>Garrett Winters</td><td>Accountant</td><td>Tokyo</td><td>63</td><td>2011/07/25</td><td>$170,750</td></tr><tr><td>Ashton Cox</td><td>Junior Technical Author</td><td>San Francisco</td><td>66</td><td>2009/01/12</td><td>$86,000</td></tr><tr><td>Cedric Kelly</td><td>Senior Javascript Developer</td><td>Edinburgh</td><td>22</td><td>2012/03/29</td><td>$433,060</td></tr><tr><td>Airi Satou</td><td>Accountant</td><td>Tokyo</td><td>33</td><td>2008/11/28</td><td>$162,700</td></tr><tr><td>Brielle Williamson</td><td>Integration Specialist</td><td>New York</td><td>61</td><td>2012/12/02</td><td>$372,000</td></tr><tr><td>Herrod Chandler</td><td>Sales Assistant</td><td>San Francisco</td><td>59</td><td>2012/08/06</td><td>$137,500</td></tr><tr><td>Rhona Davidson</td><td>Integration Specialist</td><td>Tokyo</td><td>55</td><td>2010/10/14</td><td>$327,900</td></tr><tr><td>Colleen Hurst</td><td>Javascript Developer</td><td>San Francisco</td><td>39</td><td>2009/09/15</td><td>$205,500</td></tr><tr><td>Sonya Frost</td><td>Software Engineer</td><td>Edinburgh</td><td>23</td><td>2008/12/13</td><td>$103,600</td></tr><tr><td>Jena Gaines</td><td>Office Manager</td><td>London</td><td>30</td><td>2008/12/19</td><td>$90,560</td></tr><tr><td>Quinn Flynn</td><td>Support Lead</td><td>Edinburgh</td><td>22</td><td>2013/03/03</td><td>$342,000</td></tr><tr><td>Charde Marshall</td><td>Regional Director</td><td>San Francisco</td><td>36</td><td>2008/10/16</td><td>$470,600</td></tr><tr><td>Haley Kennedy</td><td>Senior Marketing Designer</td><td>London</td><td>43</td><td>2012/12/18</td><td>$313,500</td></tr><tr><td>Tatyana Fitzpatrick</td><td>Regional Director</td><td>London</td><td>19</td><td>2010/03/17</td><td>$385,750</td></tr><tr><td>Michael Silva</td><td>Marketing Designer</td><td>London</td><td>66</td><td>2012/11/27</td><td>$198,500</td></tr><tr><td>Paul Byrd</td><td>Chief Financial Officer (CFO)</td><td>New York</td><td>64</td><td>2010/06/09</td><td>$725,000</td></tr><tr><td>Gloria Little</td><td>Systems Administrator</td><td>New York</td><td>59</td><td>2009/04/10</td><td>$237,500</td></tr><tr><td>Bradley Greer</td><td>Software Engineer</td><td>London</td><td>41</td><td>2012/10/13</td><td>$132,000</td></tr><tr><td>Dai Rios</td><td>Personnel Lead</td><td>Edinburgh</td><td>35</td><td>2012/09/26</td><td>$217,500</td></tr><tr><td>Jenette Caldwell</td><td>Development Lead</td><td>New York</td><td>30</td><td>2011/09/03</td><td>$345,000</td></tr><tr><td>Yuri Berry</td><td>Chief Marketing Officer (CMO)</td><td>New York</td><td>40</td><td>2009/06/25</td><td>$675,000</td></tr><tr><td>Caesar Vance</td><td>Pre-Sales Support</td><td>New York</td><td>21</td><td>2011/12/12</td><td>$106,450</td></tr><tr><td>Doris Wilder</td><td>Sales Assistant</td><td>Sidney</td><td>23</td><td>2010/09/20</td><td>$85,600</td></tr><tr><td>Angelica Ramos</td><td>Chief Executive Officer (CEO)</td><td>London</td><td>47</td><td>2009/10/09</td><td>$1,200,000</td></tr><tr><td>Gavin Joyce</td><td>Developer</td><td>Edinburgh</td><td>42</td><td>2010/12/22</td><td>$92,575</td></tr><tr><td>Jennifer Chang</td><td>Regional Director</td><td>Singapore</td><td>28</td><td>2010/11/14</td><td>$357,650</td></tr><tr><td>Brenden Wagner</td><td>Software Engineer</td><td>San Francisco</td><td>28</td><td>2011/06/07</td><td>$206,850</td></tr><tr><td>Fiona Green</td><td>Chief Operating Officer (COO)</td><td>San Francisco</td><td>48</td><td>2010/03/11</td><td>$850,000</td></tr><tr><td>Shou Itou</td><td>Regional Marketing</td><td>Tokyo</td><td>20</td><td>2011/08/14</td><td>$163,000</td></tr><tr><td>Michelle House</td><td>Integration Specialist</td><td>Sidney</td><td>37</td><td>2011/06/02</td><td>$95,400</td></tr><tr><td>Suki Burks</td><td>Developer</td><td>London</td><td>53</td><td>2009/10/22</td><td>$114,500</td></tr><tr><td>Prescott Bartlett</td><td>Technical Author</td><td>London</td><td>27</td><td>2011/05/07</td><td>$145,000</td></tr><tr><td>Gavin Cortez</td><td>Team Leader</td><td>San Francisco</td><td>22</td><td>2008/10/26</td><td>$235,500</td></tr><tr><td>Martena Mccray</td><td>Post-Sales support</td><td>Edinburgh</td><td>46</td><td>2011/03/09</td><td>$324,050</td></tr><tr><td>Unity Butler</td><td>Marketing Designer</td><td>San Francisco</td><td>47</td><td>2009/12/09</td><td>$85,675</td></tr><tr><td>Howard Hatfield</td><td>Office Manager</td><td>San Francisco</td><td>51</td><td>2008/12/16</td><td>$164,500</td></tr><tr><td>Hope Fuentes</td><td>Secretary</td><td>San Francisco</td><td>41</td><td>2010/02/12</td><td>$109,850</td></tr><tr><td>Vivian Harrell</td><td>Financial Controller</td><td>San Francisco</td><td>62</td><td>2009/02/14</td><td>$452,500</td></tr><tr><td>Timothy Mooney</td><td>Office Manager</td><td>London</td><td>37</td><td>2008/12/11</td><td>$136,200</td></tr><tr><td>Jackson Bradshaw</td><td>Director</td><td>New York</td><td>65</td><td>2008/09/26</td><td>$645,750</td></tr><tr><td>Olivia Liang</td><td>Support Engineer</td><td>Singapore</td><td>64</td><td>2011/02/03</td><td>$234,500</td></tr><tr><td>Bruno Nash</td><td>Software Engineer</td><td>London</td><td>38</td><td>2011/05/03</td><td>$163,500</td></tr><tr><td>Sakura Yamamoto</td><td>Support Engineer</td><td>Tokyo</td><td>37</td><td>2009/08/19</td><td>$139,575</td></tr><tr><td>Thor Walton</td><td>Developer</td><td>New York</td><td>61</td><td>2013/08/11</td><td>$98,540</td></tr><tr><td>Finn Camacho</td><td>Support Engineer</td><td>San Francisco</td><td>47</td><td>2009/07/07</td><td>$87,500</td></tr><tr><td>Serge Baldwin</td><td>Data Coordinator</td><td>Singapore</td><td>64</td><td>2012/04/09</td><td>$138,575</td></tr><tr><td>Zenaida Frank</td><td>Software Engineer</td><td>New York</td><td>63</td><td>2010/01/04</td><td>$125,250</td></tr><tr><td>Zorita Serrano</td><td>Software Engineer</td><td>San Francisco</td><td>56</td><td>2012/06/01</td><td>$115,000</td></tr><tr><td>Jennifer Acosta</td><td>Junior Javascript Developer</td><td>Edinburgh</td><td>43</td><td>2013/02/01</td><td>$75,650</td></tr><tr><td>Cara Stevens</td><td>Sales Assistant</td><td>New York</td><td>46</td><td>2011/12/06</td><td>$145,600</td></tr><tr><td>Hermione Butler</td><td>Regional Director</td><td>London</td><td>47</td><td>2011/03/21</td><td>$356,250</td></tr><tr><td>Lael Greer</td><td>Systems Administrator</td><td>London</td><td>21</td><td>2009/02/27</td><td>$103,500</td></tr><tr><td>Jonas Alexander</td><td>Developer</td><td>San Francisco</td><td>30</td><td>2010/07/14</td><td>$86,500</td></tr><tr><td>Shad Decker</td><td>Regional Director</td><td>Edinburgh</td><td>51</td><td>2008/11/13</td><td>$183,000</td></tr><tr><td>Michael Bruce</td><td>Javascript Developer</td><td>Singapore</td><td>29</td><td>2011/06/27</td><td>$183,000</td></tr><tr><td>Donna Snider</td><td>Customer Support</td><td>New York</td><td>27</td><td>2011/01/25</td><td>$112,000</td></tr></tbody></table></p>


</body>
</HTML>


---------------------------------

Now it's doing something .

However, takes forever to load.

So not good (or wrongly built).

No, it is still static.

$(document).ready(function(){
    $('#myTable').DataTable();
});

--------------------------------

https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js
https://cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css

--------------------------------

Again ..

--------------------------------


<HTML>
<head>

<meta http-equiv="expires"
content=0
/>

<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.16/css/jquery.dataTables.css">

		<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/1.10.16/js/jquery.dataTables.js"></script>



		<script type="text/javascript">

		$(document).ready( function () {
			$('#example').dataTable( {
					responsive: true,
					columnDefs: [
						{ targets: [-1, -3], className: 'dt-body-right' }
					]
				} )
				} );


		</script>

</head>


<body>

<p>An example of DataTables in action is shown below.</p></div></div>

<p><table id="example" class="display" cellspacing="0" width="100%"><thead><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></thead><tfoot><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></tfoot><tbody><tr><td>Tiger Nixon</td><td>System Architect</td><td>Edinburgh</td><td>61</td><td>2011/04/25</td><td>$320,800</td></tr><tr><td>Garrett Winters</td><td>Accountant</td><td>Tokyo</td><td>63</td><td>2011/07/25</td><td>$170,750</td></tr><tr><td>Ashton Cox</td><td>Junior Technical Author</td><td>San Francisco</td><td>66</td><td>2009/01/12</td><td>$86,000</td></tr><tr><td>Cedric Kelly</td><td>Senior Javascript Developer</td><td>Edinburgh</td><td>22</td><td>2012/03/29</td><td>$433,060</td></tr><tr><td>Airi Satou</td><td>Accountant</td><td>Tokyo</td><td>33</td><td>2008/11/28</td><td>$162,700</td></tr><tr><td>Brielle Williamson</td><td>Integration Specialist</td><td>New York</td><td>61</td><td>2012/12/02</td><td>$372,000</td></tr><tr><td>Herrod Chandler</td><td>Sales Assistant</td><td>San Francisco</td><td>59</td><td>2012/08/06</td><td>$137,500</td></tr><tr><td>Rhona Davidson</td><td>Integration Specialist</td><td>Tokyo</td><td>55</td><td>2010/10/14</td><td>$327,900</td></tr><tr><td>Colleen Hurst</td><td>Javascript Developer</td><td>San Francisco</td><td>39</td><td>2009/09/15</td><td>$205,500</td></tr><tr><td>Sonya Frost</td><td>Software Engineer</td><td>Edinburgh</td><td>23</td><td>2008/12/13</td><td>$103,600</td></tr><tr><td>Jena Gaines</td><td>Office Manager</td><td>London</td><td>30</td><td>2008/12/19</td><td>$90,560</td></tr><tr><td>Quinn Flynn</td><td>Support Lead</td><td>Edinburgh</td><td>22</td><td>2013/03/03</td><td>$342,000</td></tr><tr><td>Charde Marshall</td><td>Regional Director</td><td>San Francisco</td><td>36</td><td>2008/10/16</td><td>$470,600</td></tr><tr><td>Haley Kennedy</td><td>Senior Marketing Designer</td><td>London</td><td>43</td><td>2012/12/18</td><td>$313,500</td></tr><tr><td>Tatyana Fitzpatrick</td><td>Regional Director</td><td>London</td><td>19</td><td>2010/03/17</td><td>$385,750</td></tr><tr><td>Michael Silva</td><td>Marketing Designer</td><td>London</td><td>66</td><td>2012/11/27</td><td>$198,500</td></tr><tr><td>Paul Byrd</td><td>Chief Financial Officer (CFO)</td><td>New York</td><td>64</td><td>2010/06/09</td><td>$725,000</td></tr><tr><td>Gloria Little</td><td>Systems Administrator</td><td>New York</td><td>59</td><td>2009/04/10</td><td>$237,500</td></tr><tr><td>Bradley Greer</td><td>Software Engineer</td><td>London</td><td>41</td><td>2012/10/13</td><td>$132,000</td></tr><tr><td>Dai Rios</td><td>Personnel Lead</td><td>Edinburgh</td><td>35</td><td>2012/09/26</td><td>$217,500</td></tr><tr><td>Jenette Caldwell</td><td>Development Lead</td><td>New York</td><td>30</td><td>2011/09/03</td><td>$345,000</td></tr><tr><td>Yuri Berry</td><td>Chief Marketing Officer (CMO)</td><td>New York</td><td>40</td><td>2009/06/25</td><td>$675,000</td></tr><tr><td>Caesar Vance</td><td>Pre-Sales Support</td><td>New York</td><td>21</td><td>2011/12/12</td><td>$106,450</td></tr><tr><td>Doris Wilder</td><td>Sales Assistant</td><td>Sidney</td><td>23</td><td>2010/09/20</td><td>$85,600</td></tr><tr><td>Angelica Ramos</td><td>Chief Executive Officer (CEO)</td><td>London</td><td>47</td><td>2009/10/09</td><td>$1,200,000</td></tr><tr><td>Gavin Joyce</td><td>Developer</td><td>Edinburgh</td><td>42</td><td>2010/12/22</td><td>$92,575</td></tr><tr><td>Jennifer Chang</td><td>Regional Director</td><td>Singapore</td><td>28</td><td>2010/11/14</td><td>$357,650</td></tr><tr><td>Brenden Wagner</td><td>Software Engineer</td><td>San Francisco</td><td>28</td><td>2011/06/07</td><td>$206,850</td></tr><tr><td>Fiona Green</td><td>Chief Operating Officer (COO)</td><td>San Francisco</td><td>48</td><td>2010/03/11</td><td>$850,000</td></tr><tr><td>Shou Itou</td><td>Regional Marketing</td><td>Tokyo</td><td>20</td><td>2011/08/14</td><td>$163,000</td></tr><tr><td>Michelle House</td><td>Integration Specialist</td><td>Sidney</td><td>37</td><td>2011/06/02</td><td>$95,400</td></tr><tr><td>Suki Burks</td><td>Developer</td><td>London</td><td>53</td><td>2009/10/22</td><td>$114,500</td></tr><tr><td>Prescott Bartlett</td><td>Technical Author</td><td>London</td><td>27</td><td>2011/05/07</td><td>$145,000</td></tr><tr><td>Gavin Cortez</td><td>Team Leader</td><td>San Francisco</td><td>22</td><td>2008/10/26</td><td>$235,500</td></tr><tr><td>Martena Mccray</td><td>Post-Sales support</td><td>Edinburgh</td><td>46</td><td>2011/03/09</td><td>$324,050</td></tr><tr><td>Unity Butler</td><td>Marketing Designer</td><td>San Francisco</td><td>47</td><td>2009/12/09</td><td>$85,675</td></tr><tr><td>Howard Hatfield</td><td>Office Manager</td><td>San Francisco</td><td>51</td><td>2008/12/16</td><td>$164,500</td></tr><tr><td>Hope Fuentes</td><td>Secretary</td><td>San Francisco</td><td>41</td><td>2010/02/12</td><td>$109,850</td></tr><tr><td>Vivian Harrell</td><td>Financial Controller</td><td>San Francisco</td><td>62</td><td>2009/02/14</td><td>$452,500</td></tr><tr><td>Timothy Mooney</td><td>Office Manager</td><td>London</td><td>37</td><td>2008/12/11</td><td>$136,200</td></tr><tr><td>Jackson Bradshaw</td><td>Director</td><td>New York</td><td>65</td><td>2008/09/26</td><td>$645,750</td></tr><tr><td>Olivia Liang</td><td>Support Engineer</td><td>Singapore</td><td>64</td><td>2011/02/03</td><td>$234,500</td></tr><tr><td>Bruno Nash</td><td>Software Engineer</td><td>London</td><td>38</td><td>2011/05/03</td><td>$163,500</td></tr><tr><td>Sakura Yamamoto</td><td>Support Engineer</td><td>Tokyo</td><td>37</td><td>2009/08/19</td><td>$139,575</td></tr><tr><td>Thor Walton</td><td>Developer</td><td>New York</td><td>61</td><td>2013/08/11</td><td>$98,540</td></tr><tr><td>Finn Camacho</td><td>Support Engineer</td><td>San Francisco</td><td>47</td><td>2009/07/07</td><td>$87,500</td></tr><tr><td>Serge Baldwin</td><td>Data Coordinator</td><td>Singapore</td><td>64</td><td>2012/04/09</td><td>$138,575</td></tr><tr><td>Zenaida Frank</td><td>Software Engineer</td><td>New York</td><td>63</td><td>2010/01/04</td><td>$125,250</td></tr><tr><td>Zorita Serrano</td><td>Software Engineer</td><td>San Francisco</td><td>56</td><td>2012/06/01</td><td>$115,000</td></tr><tr><td>Jennifer Acosta</td><td>Junior Javascript Developer</td><td>Edinburgh</td><td>43</td><td>2013/02/01</td><td>$75,650</td></tr><tr><td>Cara Stevens</td><td>Sales Assistant</td><td>New York</td><td>46</td><td>2011/12/06</td><td>$145,600</td></tr><tr><td>Hermione Butler</td><td>Regional Director</td><td>London</td><td>47</td><td>2011/03/21</td><td>$356,250</td></tr><tr><td>Lael Greer</td><td>Systems Administrator</td><td>London</td><td>21</td><td>2009/02/27</td><td>$103,500</td></tr><tr><td>Jonas Alexander</td><td>Developer</td><td>San Francisco</td><td>30</td><td>2010/07/14</td><td>$86,500</td></tr><tr><td>Shad Decker</td><td>Regional Director</td><td>Edinburgh</td><td>51</td><td>2008/11/13</td><td>$183,000</td></tr><tr><td>Michael Bruce</td><td>Javascript Developer</td><td>Singapore</td><td>29</td><td>2011/06/27</td><td>$183,000</td></tr><tr><td>Donna Snider</td><td>Customer Support</td><td>New York</td><td>27</td><td>2011/01/25</td><td>$112,000</td></tr></tbody></table></p>


</body>
</HTML>


-------------------------------------

Now it shows the dropdown to select how many entries.
No sorting, though ..

Also it is dead ugly so it somehow doesn't get the css in I guess.

Let's see ..

------------------------------------


<HTML>
<head>

<meta http-equiv="expires"
content=0
/>


	<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.16/css/jquery.dataTables.min.css">


	<script type="text/javascript" language="javascript" src="//code.jquery.com/jquery-1.12.4.js">
	</script>
	<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js">
	</script>




		<script type="text/javascript">

		$(document).ready( function () {
			$('#example').dataTable()
				} );


		</script>

</head>


<body>

<p>An example of DataTables in action is shown below.</p></div></div>

<p><table id="example" class="display" cellspacing="0" width="100%"><thead><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></thead><tfoot><tr><th>Name</th><th>Position</th><th>Office</th><th>Age</th><th>Start date</th><th>Salary</th></tr></tfoot><tbody><tr><td>Tiger Nixon</td><td>System Architect</td><td>Edinburgh</td><td>61</td><td>2011/04/25</td><td>$320,800</td></tr><tr><td>Garrett Winters</td><td>Accountant</td><td>Tokyo</td><td>63</td><td>2011/07/25</td><td>$170,750</td></tr><tr><td>Ashton Cox</td><td>Junior Technical Author</td><td>San Francisco</td><td>66</td><td>2009/01/12</td><td>$86,000</td></tr><tr><td>Cedric Kelly</td><td>Senior Javascript Developer</td><td>Edinburgh</td><td>22</td><td>2012/03/29</td><td>$433,060</td></tr><tr><td>Airi Satou</td><td>Accountant</td><td>Tokyo</td><td>33</td><td>2008/11/28</td><td>$162,700</td></tr><tr><td>Brielle Williamson</td><td>Integration Specialist</td><td>New York</td><td>61</td><td>2012/12/02</td><td>$372,000</td></tr><tr><td>Herrod Chandler</td><td>Sales Assistant</td><td>San Francisco</td><td>59</td><td>2012/08/06</td><td>$137,500</td></tr><tr><td>Rhona Davidson</td><td>Integration Specialist</td><td>Tokyo</td><td>55</td><td>2010/10/14</td><td>$327,900</td></tr><tr><td>Colleen Hurst</td><td>Javascript Developer</td><td>San Francisco</td><td>39</td><td>2009/09/15</td><td>$205,500</td></tr><tr><td>Sonya Frost</td><td>Software Engineer</td><td>Edinburgh</td><td>23</td><td>2008/12/13</td><td>$103,600</td></tr><tr><td>Jena Gaines</td><td>Office Manager</td><td>London</td><td>30</td><td>2008/12/19</td><td>$90,560</td></tr><tr><td>Quinn Flynn</td><td>Support Lead</td><td>Edinburgh</td><td>22</td><td>2013/03/03</td><td>$342,000</td></tr><tr><td>Charde Marshall</td><td>Regional Director</td><td>San Francisco</td><td>36</td><td>2008/10/16</td><td>$470,600</td></tr><tr><td>Haley Kennedy</td><td>Senior Marketing Designer</td><td>London</td><td>43</td><td>2012/12/18</td><td>$313,500</td></tr><tr><td>Tatyana Fitzpatrick</td><td>Regional Director</td><td>London</td><td>19</td><td>2010/03/17</td><td>$385,750</td></tr><tr><td>Michael Silva</td><td>Marketing Designer</td><td>London</td><td>66</td><td>2012/11/27</td><td>$198,500</td></tr><tr><td>Paul Byrd</td><td>Chief Financial Officer (CFO)</td><td>New York</td><td>64</td><td>2010/06/09</td><td>$725,000</td></tr><tr><td>Gloria Little</td><td>Systems Administrator</td><td>New York</td><td>59</td><td>2009/04/10</td><td>$237,500</td></tr><tr><td>Bradley Greer</td><td>Software Engineer</td><td>London</td><td>41</td><td>2012/10/13</td><td>$132,000</td></tr><tr><td>Dai Rios</td><td>Personnel Lead</td><td>Edinburgh</td><td>35</td><td>2012/09/26</td><td>$217,500</td></tr><tr><td>Jenette Caldwell</td><td>Development Lead</td><td>New York</td><td>30</td><td>2011/09/03</td><td>$345,000</td></tr><tr><td>Yuri Berry</td><td>Chief Marketing Officer (CMO)</td><td>New York</td><td>40</td><td>2009/06/25</td><td>$675,000</td></tr><tr><td>Caesar Vance</td><td>Pre-Sales Support</td><td>New York</td><td>21</td><td>2011/12/12</td><td>$106,450</td></tr><tr><td>Doris Wilder</td><td>Sales Assistant</td><td>Sidney</td><td>23</td><td>2010/09/20</td><td>$85,600</td></tr><tr><td>Angelica Ramos</td><td>Chief Executive Officer (CEO)</td><td>London</td><td>47</td><td>2009/10/09</td><td>$1,200,000</td></tr><tr><td>Gavin Joyce</td><td>Developer</td><td>Edinburgh</td><td>42</td><td>2010/12/22</td><td>$92,575</td></tr><tr><td>Jennifer Chang</td><td>Regional Director</td><td>Singapore</td><td>28</td><td>2010/11/14</td><td>$357,650</td></tr><tr><td>Brenden Wagner</td><td>Software Engineer</td><td>San Francisco</td><td>28</td><td>2011/06/07</td><td>$206,850</td></tr><tr><td>Fiona Green</td><td>Chief Operating Officer (COO)</td><td>San Francisco</td><td>48</td><td>2010/03/11</td><td>$850,000</td></tr><tr><td>Shou Itou</td><td>Regional Marketing</td><td>Tokyo</td><td>20</td><td>2011/08/14</td><td>$163,000</td></tr><tr><td>Michelle House</td><td>Integration Specialist</td><td>Sidney</td><td>37</td><td>2011/06/02</td><td>$95,400</td></tr><tr><td>Suki Burks</td><td>Developer</td><td>London</td><td>53</td><td>2009/10/22</td><td>$114,500</td></tr><tr><td>Prescott Bartlett</td><td>Technical Author</td><td>London</td><td>27</td><td>2011/05/07</td><td>$145,000</td></tr><tr><td>Gavin Cortez</td><td>Team Leader</td><td>San Francisco</td><td>22</td><td>2008/10/26</td><td>$235,500</td></tr><tr><td>Martena Mccray</td><td>Post-Sales support</td><td>Edinburgh</td><td>46</td><td>2011/03/09</td><td>$324,050</td></tr><tr><td>Unity Butler</td><td>Marketing Designer</td><td>San Francisco</td><td>47</td><td>2009/12/09</td><td>$85,675</td></tr><tr><td>Howard Hatfield</td><td>Office Manager</td><td>San Francisco</td><td>51</td><td>2008/12/16</td><td>$164,500</td></tr><tr><td>Hope Fuentes</td><td>Secretary</td><td>San Francisco</td><td>41</td><td>2010/02/12</td><td>$109,850</td></tr><tr><td>Vivian Harrell</td><td>Financial Controller</td><td>San Francisco</td><td>62</td><td>2009/02/14</td><td>$452,500</td></tr><tr><td>Timothy Mooney</td><td>Office Manager</td><td>London</td><td>37</td><td>2008/12/11</td><td>$136,200</td></tr><tr><td>Jackson Bradshaw</td><td>Director</td><td>New York</td><td>65</td><td>2008/09/26</td><td>$645,750</td></tr><tr><td>Olivia Liang</td><td>Support Engineer</td><td>Singapore</td><td>64</td><td>2011/02/03</td><td>$234,500</td></tr><tr><td>Bruno Nash</td><td>Software Engineer</td><td>London</td><td>38</td><td>2011/05/03</td><td>$163,500</td></tr><tr><td>Sakura Yamamoto</td><td>Support Engineer</td><td>Tokyo</td><td>37</td><td>2009/08/19</td><td>$139,575</td></tr><tr><td>Thor Walton</td><td>Developer</td><td>New York</td><td>61</td><td>2013/08/11</td><td>$98,540</td></tr><tr><td>Finn Camacho</td><td>Support Engineer</td><td>San Francisco</td><td>47</td><td>2009/07/07</td><td>$87,500</td></tr><tr><td>Serge Baldwin</td><td>Data Coordinator</td><td>Singapore</td><td>64</td><td>2012/04/09</td><td>$138,575</td></tr><tr><td>Zenaida Frank</td><td>Software Engineer</td><td>New York</td><td>63</td><td>2010/01/04</td><td>$125,250</td></tr><tr><td>Zorita Serrano</td><td>Software Engineer</td><td>San Francisco</td><td>56</td><td>2012/06/01</td><td>$115,000</td></tr><tr><td>Jennifer Acosta</td><td>Junior Javascript Developer</td><td>Edinburgh</td><td>43</td><td>2013/02/01</td><td>$75,650</td></tr><tr><td>Cara Stevens</td><td>Sales Assistant</td><td>New York</td><td>46</td><td>2011/12/06</td><td>$145,600</td></tr><tr><td>Hermione Butler</td><td>Regional Director</td><td>London</td><td>47</td><td>2011/03/21</td><td>$356,250</td></tr><tr><td>Lael Greer</td><td>Systems Administrator</td><td>London</td><td>21</td><td>2009/02/27</td><td>$103,500</td></tr><tr><td>Jonas Alexander</td><td>Developer</td><td>San Francisco</td><td>30</td><td>2010/07/14</td><td>$86,500</td></tr><tr><td>Shad Decker</td><td>Regional Director</td><td>Edinburgh</td><td>51</td><td>2008/11/13</td><td>$183,000</td></tr><tr><td>Michael Bruce</td><td>Javascript Developer</td><td>Singapore</td><td>29</td><td>2011/06/27</td><td>$183,000</td></tr><tr><td>Donna Snider</td><td>Customer Support</td><td>New York</td><td>27</td><td>2011/01/25</td><td>$112,000</td></tr></tbody></table></p>


</body>
</HTML>

--------------------------

This is some sort of advanced example.

Let's backtrack a little ..

--------------------------

https://datatables.net/examples/basic_init/multi_col_sort.html

----------------------------

$(document).ready(function() {
    $('#example').DataTable( {
        columnDefs: [ {
            targets: [ 0 ],
            orderData: [ 0, 1 ]
        }, {
            targets: [ 1 ],
            orderData: [ 1, 0 ]
        }, {
            targets: [ 4 ],
            orderData: [ 4, 0 ]
        } ]
    } );
} );

------------------------------

Trying that now .

------------------------------

No luck.

This should be it, though ..

https://datatables.net/examples/basic_init/zero_configuration.html

DataTables has most features enabled by default, so all you need to do to use it with your own tables is to call the construction function: $().DataTable();.

Searching, ordering and paging goodness will be immediately added to the table, as shown in this example.

------------------------------

So, all should work.

Oh dude as it doesn't.

------------------------------

https://www.codeproject.com/Tips/844403/jQuery-Datatables-For-Beginners

------------------------------

Oh, now it works .

------------------------------

Here first working :

------------------------------


<HTML>
<head>


<script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>

<script src="https://cdn.datatables.net/1.10.4/js/jquery.dataTables.min.js"></script>
<link rel="stylesheet" href="https://cdn.datatables.net/1.10.4/css/jquery.dataTables.min.css">


<script type="text/javascript">
$(document).ready
(
function() 
{
  $('#myTesting').DataTable();
} 
);
</script>


</head>


<body>


<table id="myTesting" >

        <thead>
            <tr>
                <th>Name</th>
                <th>Position</th>
                <th>Office</th>
                <th>Age</th>
                <th>Start date</th>
                <th>Salary</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>Tiger Nixon</td>
                <td>System Architect</td>
                <td>Edinburgh</td>
                <td>61</td>
                <td>2011/04/25</td>
                <td>$320,800</td>
            </tr>
            <tr>
                <td>Garrett Winters</td>
                <td>Accountant</td>
                <td>Tokyo</td>
                <td>63</td>
                <td>2011/07/25</td>
                <td>$170,750</td>
            </tr>
            <tr>
                <td>Ashton Cox</td>
                <td>Junior Technical Author</td>
                <td>San Francisco</td>
                <td>66</td>
                <td>2009/01/12</td>
                <td>$86,000</td>
            </tr>
        </tbody>

    </table>

</body>
</HTML>

-----------------------------------

This is what we want.

Let's see how slow this is via server (not on public)

-------------------------------------

For that we need to download the sources ..

-------------------------------------

<script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>

<script src="https://cdn.datatables.net/1.10.4/js/jquery.dataTables.min.js"></script>
<link rel="stylesheet" href="https://cdn.datatables.net/1.10.4/css/jquery.dataTables.min.css">

-------------------------------------

Almost. not quite.

something is not quite right.

-------------------------------------

WOrks !!!

--------------------------------------

However, I think the css doesn't work ?

Or, maybe they set the CSS somewhere in the script ?

--------------------------------------

jQuery and all its stuff is under MIT license :

https://stackoverflow.com/questions/3902754/mit-vs-gpl-license

The MIT license is GPL-compatible. Is the GPL license MIT-compatible? i.e. I can include MIT-licensed code in a GPL-licensed product, but can I include GPL-licensed code in a MIT-licensed product?

The difference with MIT is that even if you actually distribute your proprietary code that is using the MIT licensed code, you do not have to make the code open source. You can distribute it as a closed app where the code is encrypted or is a binary. Including the MIT-licensed code can be encrypted, as long as it carries the MIT license notice.

Oh, jQuery is double license, luckily !

No - it was double license until 2102

https://blog.jquery.com/2012/09/10/jquery-licensing-changes/

One simplification we made was to remove the GNU General Public License (GPL), leaving only the MIT License. Having just one license option makes things easier for the Foundation to manage and eliminates confusion that existed about the Foundation’s previous dual-licensing policy. 

However, this doesn’t affect your ability to use any of the Foundation’s projects. You are still free to take a jQuery Foundation project, make changes, and re-license it under the GPL if your situation makes that desirable. The Free Software Foundation site confirms that the MIT License is a “lax, permissive non-copyleft free software license, compatible with the GNU GPL.”

--------------------------------------

OK, so MIT license is compatible to be added into GPL work.

--------------------------------------

Well any case now.

--------------------------------------

Why is my thingie not showing the way I wanted ????

---------------------------------------

https://datatables.net/examples/styling/display.html

---------------------------------------

Ah, the TABLE needs to have a CLASS,
which then puts the stripes on it etc !

---------------------------------------

Well that's good ..

---------------------------------------

<table id="example" class="display" cellspacing="0" width="100%">

Yes :) :)

---------------------------------------

And here we have it :

---------------------------------------

/home/molhaem2/telenius/jQueryTest
[telenius@deva jQueryTest]$ tree
.
|-- jquery-1.11.1.min.js -> ../jQuery/jquery-1.11.1.min.js
|-- jquery-1.12.4.min.js -> ../jQuery/jquery-1.12.4.min.js
|-- jquery-3.2.1.min.js -> ../jQuery/jquery-3.2.1.min.js
|-- jquery.dataTables.min.css -> ../jQuery/jquery.dataTables.min.css
|-- jquery.dataTables.min.js -> ../jQuery/jquery.dataTables.min.js
|-- site-examples.css -> ../jQuery/site-examples.css
`-- test.html

0 directories, 7 files
[telenius@deva jQueryTest]$ 

[telenius@deva jQueryTest]$ cat test.html 

<HTML>
<head>


<script src="jquery-3.2.1.min.js"></script>

<script src="jquery.dataTables.min.js"></script>

<link rel="stylesheet" href="jquery.dataTables.min.css">

<style media="screen" type="text/css">

html body {
   
    margin: auto;
    width: 90%;
    padding: 10px;
    border: 3px solid #f0f0f0;
    max-width:900px;

    line-height: 150%;
    font-family: Helvetica;    
    background-color: #ffffff;
}

</style>

<script type="text/javascript">
$(document).ready
(
function() 
{
  $('#myTesting').DataTable();
} 
);
</script>


</head>


<body>


<table id="myTesting" class="display">

        <thead align="left">
            <tr>
                <th>Name</th>
                <th>Position</th>
                <th>Office</th>
                <th>Age</th>
                <th>Start date</th>
                <th>Salary</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>Tiger Nixon</td>
                <td>System Architect</td>
                <td>Edinburgh</td>
                <td>61</td>
                <td>2011/04/25</td>
                <td>$320,800</td>
            </tr>
            <tr>
                <td>Garrett Winters</td>
                <td>Accountant</td>
                <td>Tokyo</td>
                <td>63</td>
                <td>2011/07/25</td>
                <td>$170,750</td>
            </tr>
            <tr>
                <td>Ashton Cox</td>
                <td>Junior Technical Author</td>
                <td>San Francisco</td>
                <td>66</td>
                <td>2009/01/12</td>
                <td>$86,000</td>
            </tr>
        </tbody>

    </table>

</body>
</HTML>
[telenius@deva jQueryTest]$ 

------------------------------------

Now, making the table of all data in pyramid ..

-------------------------------------

[telenius@deva jQueryTest]$ find /t1-data/data/hugheslab/PYRAMID/RUNS -name *PIPE_sampleComments.txt       
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me3/C57/Ter119_H3K4me3_MZ_DH_Jun_2012/rep1/mm9_jk_26Aug2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/Input/C57/Rad21input_LH_DH_Mar_2013/rep1/mm9_jt_19Oct2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/Input/C57/Ter119_HistoneInput_MZ_DH_Jun_2012/rep1/mm9_jk_31Aug2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/RAD21/C57/Rad21Cohesin_LH_DH_Mar_2013/rep2/mm9_jt_19Oct2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/RAD21/C57/Rad21Cohesin_LH_DH_Mar_2013/rep1/mm9_jt_19Oct2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119_spleen/Ezh2/C57/Ezh2_C57_Ter119_LH_DH_May_2016/rep3/mm9_ch_28Jun2017/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119_spleen/Ezh2/C57/Ezh2_C57_Ter119_LH_DH_May_2016/rep1/mm9_ch_28Jun2017/Comments_Peaks_Footprints/PIPE_sampleComments.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119_spleen/Ezh2/C57/Ezh2_C57_Ter119_LH_DH_May_2016/rep2/mm9_ch_28Jun2017/Comments_Peaks_Footprints/PIPE_sampleComments.txt

--------------------------------------

[telenius@deva jQueryTest]$ find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016 -name PIPE_*.txt 
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/PipeRun/PIPE_hubbingSymbolic.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/PipeRun/PIPE_metadata.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/PipeRun/PIPE_ChIP_metadata.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/PipeRun/PIPE_fastqPaths.txt
/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/Comments_Peaks_Footprints/PIPE_sampleComments.txt
[telenius@deva jQueryTest]$ 

---------------------------------------

[telenius@deva jQueryTest]$ tree /t1-data1/WTSA/PYRAMID/FASTQ/ChIP/mouse/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1
/t1-data1/WTSA/PYRAMID/FASTQ/ChIP/mouse/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1 [error opening dir]

( as organism and data type were moved vice versa )

[telenius@deva jQueryTest]$ tree /t1-data1/WTSA/PYRAMID/FASTQ/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1
/t1-data1/WTSA/PYRAMID/FASTQ/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1
|-- md5sums
|   |-- mdsums_R1afterCopy.txt
|   |-- mdsums_R1beforeCopy.txt
|   |-- mdsums_R1gzipped.txt
|   |-- mdsums_R1unzipped.txt
|   |-- mdsums_R2afterCopy.txt
|   |-- mdsums_R2beforeCopy.txt
|   |-- mdsums_R2gzipped.txt
|   `-- mdsums_R2unzipped.txt
|-- PIPE_ChIP_metadata.txt
|-- PIPE_fastqPaths.txt
|-- PIPE_metadata.txt
|-- PIPE_sampleComments.txt
|-- PyramidVersion.txt
|-- Ter119_H3K4me1_1.fq.gz
|-- Ter119_H3K4me1_2.fq.gz
`-- WhoStoredThis_and_WhereFastqsCameFrom.txt

1 directory, 16 files
[telenius@deva jQueryTest]$ 

WhoStoredThis_and_WhereFastqsCameFrom.txt

-----------------------------------

"Starting small"

/t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP/ter119/H3K4me1/C57/Ter119_H3K4me1_MZ_DH_Jun_2012/rep1/mm9_jk_30Aug2016/PipeRun

find /t1-data/data/hugheslab/PYRAMID/RUNS -name *PIPE_metadata.txt > filelist.txt

cat filelist.txt | sed 's/\/PipeRun\/PIPE_metadata.txt//' | sed 's/\//<td>/' | sed 's/$/</td>/'

-------------------------------------

[telenius@deva jQueryTest]$ echo "tr" | cat filelist.txt - | sed 's/\/PipeRun\/PIPE_metadata.txt//' | sed 's/\/t1-data\/data\/hugheslab\/PYRAMID\/RUNS//' | sed 's/\//\n<td>/g' | sed 's/$/<\/td>/' | sed 's/^<\/td>$/<\/tr><tr>/' | awk '{if(NR==1)print "<tr>"; else {print $0}}' | sed 's/^tr<\/td>/<\/tr>/'

--------------------------------------

[telenius@deva jQueryTest]$ echo "tr" | cat filelist.txt - | sed 's/\/Comments_Peaks_Footprints\/PIPE_sampleComments.txt$//' | sed 's/\/t1-data\/data\/hugheslab\/PYRAMID\/RUNS//' | sed 's/\//\n<td>/g' | rev | sed 's/_/\//' | sed 's/_/\//' | rev | sed 's/\//\n<td>/g' | sed 's/$/<\/td>/' | sed 's/^<\/td>$/<\/tr><tr>/' | awk '{if(NR==1)print "<tr>"; else {print $0}}' | sed 's/^tr<\/td>/<\/tr>/' > testi.txt

---------------------------------------

Easier to make it with paste.

------------------------------------------

[telenius@deva jQueryTest]$ cat filelist.txt | sed 's/\//\t/g' | cut -f 9-14
ter119  H3K4me1 C57     Ter119_H3K4me1_MZ_DH_Jun_2012   rep1    mm9_jk_30Aug2016
ter119  H3K4me3 C57     Ter119_H3K4me3_MZ_DH_Jun_2012   rep1    mm9_jk_26Aug2016
ter119  Input   C57     Rad21input_LH_DH_Mar_2013       rep1    mm9_jt_19Oct2016
ter119  Input   C57     Ter119_HistoneInput_MZ_DH_Jun_2012      rep1    mm9_jk_31Aug2016
ter119  RAD21   C57     Rad21Cohesin_LH_DH_Mar_2013     rep2    mm9_jt_19Oct2016
ter119  RAD21   C57     Rad21Cohesin_LH_DH_Mar_2013     rep1    mm9_jt_19Oct2016
ter119_spleen   Ezh2    C57     Ezh2_C57_Ter119_LH_DH_May_2016  rep3    mm9_ch_28Jun2017
ter119_spleen   Ezh2    C57     Ezh2_C57_Ter119_LH_DH_May_2016  rep1    mm9_ch_28Jun2017
ter119_spleen   Ezh2    C57     Ezh2_C57_Ter119_LH_DH_May_2016  rep2    mm9_ch_28Jun2017
[telenius@deva jQueryTest]$ cat filelist.txt | sed 's/\//\t/g' | cut -f 9-14 > cutted.txt

------------------------------------------

cat filelist.txt | sed 's/\//\t/g' | cut -f 9-11 > cutted911.txt
cat filelist.txt | sed 's/\//\t/g' | cut -f 12 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted12.txt
cat filelist.txt | sed 's/\//\t/g' | cut -f 14 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted14.txt
cat filelist.txt | sed 's/\//\t/g' | cut -f 13 > cutted13.txt
paste cutted911.txt cutted12.txt cutted13.txt cutted14.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<td><\/td>/g' | sed 's/$/<\/td<\/tr>/' > parsed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat begin.txt parsed.txt end.txt > test3.html 

----------------------

Oh dude it auto-enables multi-column sorting !!!

https://datatables.net/examples/basic_init/multi_col_sort.html

----------------------

That is amazing.

Amazing.

----------------------

Making the full table then !

-----------------------

nohup nice find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP -name PIPE_sampleComments.txt > mousechipfilelist.txt &
nohup nice find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ATAC -name PIPE_sampleComments.txt > mouseaccessibilityfilelist.txt &

nohup nice find /t1-data/data/hugheslab/PYRAMID/RUNS/human/ChIP -name PIPE_sampleComments.txt > humanchipfilelist.txt &
nohup nice find /t1-data/data/hugheslab/PYRAMID/RUNS/human/ATAC -name PIPE_sampleComments.txt > humanaccessibilityfilelist.txt &


nohup nice find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/DNaseI -name PIPE_sampleComments.txt >> mouseaccessibilityfilelist.txt &
nohup nice find /t1-data/data/hugheslab/PYRAMID/RUNS/human/DNaseI -name PIPE_sampleComments.txt >> humanaccessibilityfilelist.txt &


------------------------------------------

doItForChip(){

cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 9-11 > cutted911.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 12 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted12.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 14 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted14.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 13 > cutted13.txt
paste cutted911.txt cutted12.txt cutted13.txt cutted14.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat chipbegin.txt parsed.txt end.txt > ${filelist}.html 

}


doItForAccessibility(){

cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 8-10 > cutted810.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 11 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted11.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 13 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted13.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 12 > cutted12.txt
paste cutted810.txt cutted11.txt cutted12.txt cutted13.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat accessibilitybegin.txt parsed.txt end.txt > ${filelist}.html 

}

# -----------------------

filelist="mousechip"
doItForChip

filelist="humanchip"
# doItForChip


# -----------------------

filelist="mouseaccessibility"
doItForAccessibility

filelist="humanaccessibility"
# doItForAccessibility

----------------------------

That is amazing.

That really is.

----------------------------

Making the full script :

----------------------------

#!/bin/bash

echo 
echo "Generating PYRAMID html listings .."
echo
echo
hostname
echo
pwd
echo
echo $0
echo
date
echo
module purge
module list
echo


doItForChip(){

cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 9-11 > cutted911.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 12 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted12.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 14 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted14.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 13 > cutted13.txt
paste cutted911.txt cutted12.txt cutted13.txt cutted14.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat chipbegin.txt parsed.txt end.txt > ${filelist}.html 

}


doItForAccessibility(){

cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 8-10 > cutted810.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 11 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted11.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 13 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted13.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 12 > cutted12.txt
paste cutted810.txt cutted11.txt cutted12.txt cutted13.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat accessibilitybegin.txt parsed.txt end.txt > ${filelist}.html 

}

# -----------------------

find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP -name PIPE_sampleComments.txt > mousechipfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ATAC -name PIPE_sampleComments.txt > mouseaccessibilityfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/DNaseI -name PIPE_sampleComments.txt >> mouseaccessibilityfilelist.txt &

find /t1-data/data/hugheslab/PYRAMID/RUNS/human/ChIP -name PIPE_sampleComments.txt > humanchipfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/human/ATAC -name PIPE_sampleComments.txt > humanaccessibilityfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/human/DNaseI -name PIPE_sampleComments.txt >> humanaccessibilityfilelist.txt &

# -----------------------

filelist="mousechip"
doItForChip

filelist="humanchip"
# doItForChip


# -----------------------

filelist="mouseaccessibility"
doItForAccessibility

filelist="humanaccessibility"
# doItForAccessibility


echo
date
echo
echo "All done !" 
echo


----------------------------


#!/bin/bash

echo 
echo "Generating PYRAMID html listings .."
echo
echo
hostname
echo
pwd
echo
echo $0
echo
date
echo
module purge
module list
echo


doItForChip(){

cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 9-11 > cutted911.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 12 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted12.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 14 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted14.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 13 > cutted13.txt
paste cutted911.txt cutted12.txt cutted13.txt cutted14.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat chipbegin.txt parsed.txt end.txt > ${filelist}.html 

cp ${filelist}.html ../HTML/.

}


doItForAccessibility(){

cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 8-10 > cutted810.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 11 | rev | sed 's/_/\t/' | sed 's/_/\t/' | sed 's/_/\t/'  | sed 's/_/\t/'| rev > cutted11.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 13 | rev | sed 's/_/\t/' | sed 's/_/\t/' | rev > cutted13.txt
cat ${filelist}filelist.txt | sed 's/\//\t/g' | cut -f 12 > cutted12.txt
paste cutted810.txt cutted11.txt cutted12.txt cutted13.txt > cuttedTabbed.txt

cat cuttedTabbed.txt | sed 's/^/<tr><td>/' | sed 's/\t/<\/td><td>/g' | sed 's/$/<\/td><\/tr>/' > parsed.txt
cat accessibilitybegin.txt parsed.txt end.txt > ${filelist}.html 

cp ${filelist}.html ../HTML/.

}

# -----------------------

rm -rf TEMPdir
mkdir TEMPdir
cd TEMPdir

# -----------------------

find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ChIP -name PIPE_sampleComments.txt > mousechipfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/ATAC -name PIPE_sampleComments.txt > mouseaccessibilityfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/mouse/DNaseI -name PIPE_sampleComments.txt >> mouseaccessibilityfilelist.txt &

find /t1-data/data/hugheslab/PYRAMID/RUNS/human/ChIP -name PIPE_sampleComments.txt > humanchipfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/human/ATAC -name PIPE_sampleComments.txt > humanaccessibilityfilelist.txt &
find /t1-data/data/hugheslab/PYRAMID/RUNS/human/DNaseI -name PIPE_sampleComments.txt >> humanaccessibilityfilelist.txt &

# -----------------------

filelist="mousechip"
doItForChip

filelist="humanchip"
# doItForChip


# -----------------------

filelist="mouseaccessibility"
doItForAccessibility

filelist="humanaccessibility"
# doItForAccessibility

# -----------------------

rm -rf TEMPdir


echo
date
echo
echo "All done !" 
echo


----------------------------

/home/molhaem2/telenius/PYRAMID/Dnase/pyramidLister/updateHtmlTables.sh

----------------------------

viewing commands :

firefox /home/molhaem2/telenius/PYRAMID/Dnase/pyramidLister/HTML/mouseaccessibility.html
firefox /home/molhaem2/telenius/PYRAMID/Dnase/pyramidLister/HTML/mousechip.html


firefox /home/molhaem2/telenius/PYRAMID/Dnase/pyramidLister/HTML/GEOmouseaccessibility.html
firefox /home/molhaem2/telenius/PYRAMID/Dnase/pyramidLister/HTML/GEOmousechip.html

------------------------------
