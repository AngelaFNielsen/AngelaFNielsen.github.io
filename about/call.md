API: Call
=================

#### Purpose 
The Call API lets you lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum.
#### Audience 
This documentation is designed for people familiar with Python. If you are not familiar with Python, you can find many Python tutorials available  <a href="https://towardsdatascience.com/how-to-use-riot-api-with-python-b93be82dbbd6" title="Riot Games API How To">here</a>.

```
find_champion.

champion_data = [
 {
   'name': 'ahri',
   'role':  'mid lane',
   'origin': 'vastaya'
 },
 {
   'name': 'teemo',
   'role': 'top lane',
   'origin': 'bandle city'
 },
 {
   'name':'gangplank',
   'role': 'top lane',
   'origin': 'bilgewater'
 },
 {
   'name': 'sona',
   'role': 'support',
   'origin': 'ionia'
 },
 {
   'name': 'miss fortune',
   'role': 'marksman',
   'origin': 'bilgewater'
 }
]

def find_champion(name=None, role=None, origin=None):
 champion_suggestions = []
 for champ in champion_data:
   if name:
     if champ['name'] == name:
       return [champ]
   if role:
     if champ['role'] != role:
       continue
   if origin:
     if champ['origin'] != origin:
       continue
   champion_suggestions.append(champ)
 return champion_suggestions
```
#### View the **Call** API Response
Let's look at the result. lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum. lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum.

<em>Screenshot of code</em>

#### Verify
Test your <a href="https://extendsclass.com/python.html" title="Python Tester">code</a>.

#### Troubleshoot
lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum. lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum. lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum.

#### Recommended Reading
- <a href="https://github.com/AngelaFNielsen/AngelaFNielsen.github.io/blob/main/about/overview.md" title="Support">Overview</a>
- <a href="https://github.com/AngelaFNielsen/AngelaFNielsen.github.io/blob/main/about/support.md" title="Support">Support</a>
