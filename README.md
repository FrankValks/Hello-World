# Hello-World
<head>
	<!-- We pasted the generated code from the Issue Collector here, after choosing a custom trigger -->

	<!-- This is the script for the issue collector feedback form -->
    <script type="text/javascript" src="https://aginic.atlassian.net/s/d41d8cd98f00b204e9800998ecf8427e-T/yzhftq/b/15/a44af77267a987a660377e5c46e0fb64/_/download/batch/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector/com.atlassian.jira.collector.plugin.jira-issue-collector-plugin:issuecollector.js?locale=en-UK&collectorId=697085bc"></script>


 
	<!-- This is the script for specifying the custom trigger.  We've replaced 'myCustomTrigger' with 'feedback-button' -->

	<script type="text/javascript">
		window.ATL_JQ_PAGE_PROPS =  {
			"triggerFunction": function(showCollectorDialog) {
				//Requries that jQuery is available! 
				jQuery("#feedback-button").click(function(e) {
					e.preventDefault();
					showCollectorDialog();
				});
			}
		};
	</script>


</head>
 
<body>

	<h2>JIRA Issue Collector Demo</h2>
	<a href="#" id="feedback-button" class='btn btn-primary btn-large'>Report feedback</a>

</body>