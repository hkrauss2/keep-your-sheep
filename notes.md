### What is Battle Dragons?
[Battle Dragons](http://battledragons.com/) is a strategy game for iOS and Android where you build a fortress and command a dragon army! Gold is mined to build up defenses and sheep are raised to feed the dragon troops.

### What is Keep Your Sheep?
Keep Your Sheep is intended to be a web site featuring gameplay tips and tools to help users identify the best troop combinations.

### What features will version 1 of the site have?
1. **Administration**
  1. Basic account management with the following roles
    1. **Admin**: Can add/manage users in all roles
    2. **Author**: Can add content to the Tips section
    3. **Basic**: Can register and manage their own account.
2. **Tips**
  1. A rudimentary CMS with html elements offered through markdown
  2. Display list of articles by *category* or *date*
  2. Display individual articles
3. **Tools**
  1. **Dragon Stats**: Will display information for each dragon troop at each level. Available to all users, including anonymous.
  2. **Army Profile**: Alows Basic users to create and manage collections of dragon troops. Summary information will display for each collection such as the total cost of the troops and time to create.
  3. **Spell Profile**: Same as the **Army Profile** but contains the various spells available to use during an attack.
  4. **Attack Profile**: Allows **Basic** users to combine **Army** and **Spell Profiles** into an overall **Attack Profile**.

### What will we use to build this awesomeness!
1. **Database**: Unknown at this point. Looking for good fit for the Java middleware.
2. **Web Server**: Same as above
3. **Server-Side Components**: Since this project is intended to be Java training, some type of Java server technology will be used. I need advice on the specifics.
4. **Client**: This will be a browser client implemented as a Single Page Application using Angular, Bootstrap and other JS frameworks as needed (example: toastr, underscore, etc...).
