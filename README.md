$myDoc = get-childitem C:\Users\eddiexiong\Documents
$myList = $myDoc | where {$_.extension -eq ".docx"}
$myList | format-table Name
