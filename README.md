# AccessControlManager
Computer Security at DePaul University

Access Control: Securing documents at a law firm
Scenario
A law firm employs attorneys, law clerks, paralegals, and administrative assistants. A list of personnel follows:
Attorneys
  Bard
  Karen
Law clerks
  Sam
  Kevin
Paralegals
  Mary
  Tom
Administrative assistants
  Bob
  Becky
  
The personnel produce many documents related to their work. The attorneys direct the creation of client documents and all other personnel work on these documents. Personnel record their time working on the documents in billing documents, referred to as billings. As court dates and meetings are scheduled, entries are added to a calendar program. For purposes of this assignment, assume that each calendar entry is stored in a separate file in order to control access.
The documents that you must safeguard relate to three clients: Jones, Johnson, and Santana. The documents are as follows:

Client documents
  Jones-Pleading1.txt
  Jones-Pleading2.txt
  Johnson-Contract1.txt
  Johnson-Contract2.txt
  Santana-Pleading1.txt
  Santana-Pleading2.txt
  
Billings
  Jones-Bill1.txt
  Jones-Bill2.txt
  Johnson-Bill1.txt
  Johnson-Bill2.txt
  Santana-Bill1.txt
  Santana-Bill2.txt

Calendar entries
  Jones-Court1.txt
  Jones-Court2.txt
  Johnson-Meeting1.txt
  Johnson-Meeting2.txt
  Santana-Court1.txt
  Santana-Court2.txt

Personnel are assigned to client matters as follows:
Supervising Attorneys
Atty: Bard
Supervises: Mary, Bob
Atty: Karen
Supervises: Tom, Becky

Matter assignments
Jones
Attorneys: Bard
Law clerks: Sam
Paralegals: Mary
Admin Assts.: Bob

Santana
Attorneys: Bard
Law clerks: Sam
Paralegals: Mary
Admin Assts.: Bob

Johnson
Attorneys: Karen
Law clerks: Kevin
Paralegals: Tom
Admin Assts.: Becky

Rules
Access to documents must be restricted according to the following criteria:
All personnel can read all client documents.
Only personnel assigned to a matter for a client can write to client documents for that matter.
All personnel can read all calendar entries but the only person who can modify a calendar entry is the person who created it.
Attorneys and law clerks can read and write billings on every case.
Paralegals and administrative assistants can read and write billings only on cases assigned to their supervising attorney.
