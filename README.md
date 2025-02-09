# cloud.web360.dev


Ai UX examples using supabase and shadui, compatible with lovable.dev and other frameworks

[/ui-ai-card](/ui-ai-card) why structure your data when you can extract and display it at runtime?

[/ui-supabase-table](/ui-supabase-table) ever wanted to display a supabase table directly with advanced search on top of it?

[/ui-csv-data-enrichment](/ui-csv-data-enrichment) what csv would you let your customers enrich? events? or shopping orders?



Long term advanced Agents with tools in under 100 lines of code?

[/agent-pa.py](/agent-pa.py) 

[/agent-sdr.py](/agent-sdr.py) a full blown agent sdr that manages a crm? wild.

[/personal-assistant](/personal-assistant) an agent that can research, update your documents, and manage emails campaigns in under 100 lines of code?



API usage

```bash

GET https://api.web360.dev/docs -> str: markdown agent tool docs schema

POST https://api.web360.dev/web {query (str): search query or url} -> str /df: search results or a cleaned web page rendering, use url/idx+1 to scroll

POST https://api.web360.dev/database/info {limit: 10}  -> str: database schemas and summary of recent database transactions

POST https://api.web360.dev/database/create {tablename: str, columns: str, examples: str} -> str (summary), 

POST https://api.web360.dev/database/search {query: sql or keyword search query} -> str / df: returns md of top 10.

POST https://api.web360.dev/database/insert { tablename: str, values: str }



```
