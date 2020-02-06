
NOTE IDEA: Requesting improvement : 

workflow:todo="create-missing-misp-taxonomy"
Create missing MISP taxonomy to tagged additonnal task(e.g. a new category of tag)

workflow:todo="review-before-adding-into-IDS"
Review is required before publishing the information into IDS

workflow:todo="add-into-IDS"
Publishing the information into IDS

workflow:todo="review-for-positive-false"
Review the the information tagged to limit the number of positives-false 

Taxonomy added object 

        {
          "value": "create-missing-misp-taxonomy",
          "expanded": "Create missing MISP taxonomy to tagged additonnal task(e.g. a new category of tag)"
        },
        {
          "value": "review-before-adding-into-IDS",
          "expanded": "Review is required before publishing the information into IDS"
        },
        {
          "value": "add-into-IDS",
          "expanded": "Publishing the information into IDS"
        },
        {
          "value": "review-for-positive-false",
          "expanded": "Review the the information tagged to limit the number of positives-false "
        },



________________________________________________________________________________________

Adding Taxonomie workflow from MISP on the Map Guidelines Version 4  

source : https://www.misp-project.org/taxonomies.html#_workflow
Taxonomy : https://github.com/MISP/misp-taxonomies/blob/master/workflow/machinetag.json

workflow namespace available in JSON format at this location. The JSON format can be freely reused in your application or automatically enabled in MISP taxonomy.
Workflow support language is a common language to support intelligence analysts to perform their analysis on data and information.

todo
Todo are the actions to be performed by one or more analyst(s) to apply cognitive methods, evaluation(s), weightening information, to validate hypothesis or complete additional tasks to improve the overall information or data being tagged with a todo.

workflow:todo="expansion"
Expansion need to be applied to expand the information tagged

workflow:todo="review"
Additional review is required to reach a certain level of validation of the information tagged

workflow:todo="review-for-privacy"
Additional review is required to ensure privacy of the information tagged

workflow:todo="review-before-publication"
Review is required before publishing the information tagged

workflow:todo="release-requested"
Release of the information tagged is requested (often after the review process

workflow:todo="review-for-false-positive"
Review the the information tagged to limit the number of false-positives and potentially remove any IDS/automation flag to avoid automation of the false-positives

workflow:todo="review-the-source-credibility"
Review the source credibility and add the corresponding marking like admiralty-scale on the origin

workflow:todo="add-missing-misp-galaxy-cluster-values"
Add potential MISP galaxy cluster values missing about the information tagged

workflow:todo="create-missing-misp-galaxy-cluster"
Create missing MISP galaxy cluster about the information tagged

workflow:todo="create-missing-misp-galaxy-cluster-relationship"
create missing MISP galaxy cluster relationships (e.g. relationships between MISP clusters)

workflow:todo="create-missing-misp-galaxy"
Create missing MISP galaxy at large about the information tagged (e.g. a new category of malware or activity)

workflow:todo="create-missing-relationship"
Create missing relationship about the information tagged (e.g. create new relationship between MISP objects)

workflow:todo="add-context"
Add contextual information about the information tagged

workflow:todo="add-tagging"
Add adequate tagging and classification about the information tagged

workflow:todo="check-passive-dns-for-shared-hosting"
Check Passive DNS (or similar techniques) to review if the information tagged is used within shared hosting

workflow:todo="review-classification"
Review the classification of the information tagged to ensure adequate marking of the information before publication

workflow:todo="review-the-grammar"
Review the grammar of the information tagged to improve the overall quality

workflow:todo="do-not-delete"
Element that should not be deleted (without asking)

workflow:todo="add-mitre-attack-cluster"
Describe cyber adversary behavior using MITRE ATT&CK

workflow:todo="additional-task"
Used to point an additional task that can not be describe by the rest of the taxonomy and need to be done

workflow:todo="create-event"
A new MISP event need to be created from the tag reference

workflow:todo="preserve-evidence"
Preseve evidence mentioned in the information tagged

state
State are the different states of the information or data being tagged.

Exclusive flag set which means the values or predicate below must be set exclusively.
workflow:state="incomplete"
Incomplete means that the information tagged is incomplete and has potential to be completed by other analysts, technical processes or the current analysts performing the analysis

workflow:state="complete"
Complete means that the information tagged reach a state of completeness with the current capabilities of the analyst

workflow:state="draft"
Draft means the information tagged can be released as a preliminary version or outline

workflow:state="ongoing"
Analyst is currently working on this analysis. To remove when there is no more work to be done by the analyst.