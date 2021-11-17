# The Tyro Collective

## Mission Statement

The Collective's mission is to help members of all levels of experience contribute to and improve the table-top industry, to empower members to pursue their specialties on equal footing, and to provide a platform for collective creation.

## Projects

The Tyro Collective currently runs the following projects:

### The Tyro

[The Tyro](http://newsletter.tyro.group) newsletter, focusing on tabletop self-help resources. Check it out [here](http://newsletter.tyro.group).

- Submission of content or ideas for The Tyro may be done by filling out [this form](https://forms.gle/PZTjnyLAnymbJr9c7).

## Regular Meetings

Meetings run on a regular basis, on the last monday of each month, at 5pm EDT/10pm BST. Occasionally extra meetings will be coordinated on an ad-hoc basis. Join the discord (linked below) to find out more.

### Next meeting (in your local time):

<script>

function lastMondayOfMonth() {
    let d = new Date();
    d.setMonth(d.getMonth() + 1);
    d.setDate(0);
    d.setDate(d.getDate() - (d.getDay() - 1));
    d.setHours(18);
    d.setMinutes(0);
    d.setSeconds(0);

    // might be past it already
    var now = new Date();
    if(d < now) 
    {
        d.setMonth(d.getMonth()+1);
        d.setDate(0);
        d.setDate(d.getDate() - (d.getDay() - 1));
    }

    return d;
}

var d = lastMondayOfMonth();
var options = { dateStyle: "long", timeStyle: "long" };
document.getElementById("next-meeting-in-your-local-time").appendChild(document.createTextNode(" " + d.toLocaleString([], options)));
</script>

---

## Contact

The Tyro Collective currently interacts on the RPG Kitchen Discord server. Join [here](https://discord.gg/sStDEP62h4):

[![Discord Invite Link](./discord-icon.png)](https://discord.gg/sStDEP62h4)

