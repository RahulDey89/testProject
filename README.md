


# testProject
fiddling around 

Pom example 
    
https://svn.apache.org/viewvc/maven/pom/tags/maven-parent-26/pom.xml?view=markup#l1069


ODM tutorial-
#
http://www.ibm.com/support/knowledgecenter/SSQPJS_8.0.0/com.ibm.wodm.family.overview/understandinstall_topics/tpc_odm_composition.html

#
http://pic.dhe.ibm.com/infocenter/dmanager/v7r5/index.jsp?topic=%2Fcom.ibm.decisions.installing%2FContent%2FBusiness_Rules%2F_pubskel%2FInfocenter_Primary%2Fps_Decisions_Installing22.html


for j2ee connections 
#
http://pic.dhe.ibm.com/infocenter/brjrules/v7r0m3/index.jsp?topic=%2Fcom.ibm.websphere.ilog.jrules.doc%2FContent%2FBusiness_Rules%2FDocumentation%2F_pubskel%2FJRules%2Fps_JRules_Global31.html

#Role based
http://pic.dhe.ibm.com/infocenter/brjrules/v7r0m3/index.jsp?topic=%2Fcom.ibm.websphere.ilog.jrules.doc%2FContent%2FBusiness_Rules%2FDocumentation%2F_pubskel%2FJRules%2Fps_JRules_Global31.html



for javascript from submit
#function uploadFile() {

	for(var i=0;i<document.getElementById('fileToUpload').files.length;i++){  

	var xhr = new XMLHttpRequest();

	   var fr = 'param='+document.getElementById('survey-canvas').innerHTML;

        var fd = new FormData();

        fd.append("author", "itest");

        fd.append("form", fr);

        xhr.open("POST", "frmsubmit");
		
        xhr.send(fr);	 -- xhr.send(fd);

		}

#### get param
	BufferedReader reader = null;
		try {
			reader = httpServletRequest.getReader();
		
	   
	    while ((str = reader.readLine()) != null)
	    {
	        System.out.println(str);
	        html = str;
	    }

	}
