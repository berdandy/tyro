# The Tyro Collective

## Mission Statement

The Collective's mission is to help members of all levels of experience contribute to and improve the table-top industry, to empower members to pursue their specialties on equal footing, and to provide a platform for collective creation.

## Regular Meetings

Meetings run on a regular basis, on the last monday of each month, at 5pm EDT/10pm BST. Occasionally extra meetings will be coordinated on an ad-hoc basis. Join the discord (linked below) to find out more.

### Next meeting (in your local time):

<script>

function lastMondayOfMonth() {
  var d = new Date();
  d.setMonth(d.getMonth()+1);
  d.setDate(0); // last day of *PREVIOUS* month, hence the +1 above. Stupid API
  d.setUTCHours(21);
  d.setUTCMinutes(0);
  d.setUTCSeconds(0);
  d.setUTCDate(d.getUTCDate() - (d.getUTCDay() - 1)); // 1 == Monday;
  return d;
}

var d = lastMondayOfMonth();
document.getElementById("next-meeting-in-your-local-time").appendChild(document.createTextNode(" " + d.toLocaleString()));
</script>

---

## Contact

The Tyro Collective primarily interacts on the RPG Kitchen Discord server. Join [here](https://discord.gg/sStDEP62h4):

[![Discord Invite Link](./discord-icon.png)](https://discord.gg/sStDEP62h4)

