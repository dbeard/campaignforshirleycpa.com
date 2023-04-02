---
title: Invest in Shirley - Vote Yes on May 2nd!
feature_text: 
feature_image: "/assets/TownCenter_4a.jpg"
excerpt: "Alembic is a starting point for [Jekyll](https://jekyllrb.com/) projects. Rather than starting from scratch, this boilerplate is designed to get the ball rolling immediately. Install it, configure it, tweak it, push it."
---

The Community Preservation Act (CPA) is a Massachusetts state law enacted in 2000 that enables cities and towns to create a dedicated fund that can be spent on projects that enhance the community. 194 Massachusetts cities and towns have adopted the CPA including Shirley neighbors Ayer, Groton, Harvard, Lancaster and Pepperell.

Shirley will be voting to adopt the CPA on May 2nd. Make a difference by voting yes!

<a class="button" href="#ccblock" onclick="document.getElementById('ccblock').style.display = 'block';">Signup for email updates!&nbsp; <svg width="16" height="16" class="icon  icon--email" role="img" alt="email"><title>email</title><use xlink:href="#email" fill="CurrentColor"></use></svg>
</a>

## Frequently Asked Questions

### When is the vote for the Shirley CPA?

Tuesday, May 2nd

### Who can vote?

All voters registered in Shirley are eligible to vote on May 2nd. 

### What types of projects are eligible for CPA funds?

 - Open space & outdoor recreation
 - Affordable housing
 - Historic preservation

### How are the projects chosen?

A Community Preservation Committee (CPC) is formed following adoption of CPA. Projects are proposed by community residents or Shirley boards and commissions and brought before Town Meeting by the CPC. Projects require a majority vote at Town Meeting to qualify for funding.

### Where does the money come from?

An annual 1% surcharge would be added to Shirley property tax bills, both residential and commercial, amounting to $40 annually for the average single-family homeowner in Shirley. The state matches the funds collected at an average rate of 32%.

### Are there exemptions from the surcharge?

 - Yes – $100,000 of property value is excluded when calculating the surcharge.
 - Yes – Low and moderate income seniors over 60 and low income residents of any age may apply for exemptions.
 - Yes – Any portion of the property tax that is exempt under Massachusetts General Law Chapter 59 is also be exempt from the surcharge.

### How much money would the CPA raise annually in Shirley?

Using FY23 as an example, the total amount raised by the CPA (surcharge plus state match) would have been about $134,000. The money raised annually can be spent on current projects and/or saved for future projects.

### How can I calculate what the CPA will cost me, personally?

The CPA, if passed in Shirley, would comprise a 1% surcharge on assessed property minus a 100k exemption, which one can easily figure out by using the simple calculator below. The assessed value of your property can be found in your most recent tax bill. Please note that the assessed value is **NOT** the same as the market value of your home!

<fieldset class="fieldset form__fieldset">
<legend class="legend form__legend">CPA Calculator</legend>
<label class="label" for="assessed-value">Your Assessed Property Value:</label>
<input class="input" id="assessed-value" type="number" name="value" value="" placeholder="100000" required="required" min="0" max="20000000" />
<table>
    <tr>
        <td>Assessed value - 100k CPA exemption:</td>
        <td style="font-weight: bold;" id="minus-exemption">$0</td>
    </tr>
    <tr>
        <td id="taxed-value-description">Shirley tax rate (0.01418) x CPA exempt value:</td>
        <td style="font-weight: bold;" id="taxed-value">$0.00</td>
    </tr>
    <tr>
        <td id="annual-surcharge-description">Annual CPA surcharge (1% of taxed value):</td>
        <td style="font-weight: bold;" id="annual-surcharge">$0.00</td>
    </tr>
    <tr>
        <td>Per quarter rate of CPA surcharge:</td>
        <td style="font-weight: bold;" id="quarterly-surcharge">$0.00</td>
    </tr>
</table>
</fieldset>
<script>

document.getElementById('assessed-value').addEventListener('input', function(evt){

    var assessedValue = evt.target.value;

    //Force it to zero if less than zero or not a number
    if(isNaN(assessedValue) || assessedValue < 0){
        assessedValue = 0;
    }

    var exemptValue = assessedValue - 100000;
    if(exemptValue < 0){
        exemptValue = 0;
    }

    var taxedValue = (0.01418 * exemptValue).toFixed(2);
    var annualSurcharge = (0.01 * taxedValue).toFixed(2);
    var quarterlySurcharge = (annualSurcharge / 4).toFixed(2);

    document.getElementById("minus-exemption").innerHTML = "$" + exemptValue.toLocaleString("en-US");
    document.getElementById("taxed-value-description").innerHTML = "Shirley tax rate (0.01418) x $" + exemptValue.toLocaleString("en-US") + ":";
    document.getElementById("taxed-value").innerHTML = "$" + taxedValue;
    document.getElementById("annual-surcharge-description").innerHTML = "Annual CPA surcharge (1% of $" + taxedValue + "):";
    document.getElementById("annual-surcharge").innerHTML = "$" + annualSurcharge;
    document.getElementById("quarterly-surcharge").innerHTML = "$" + quarterlySurcharge;
});

</script>
<br>

<!-- (Your annual tax amount  x  1%) - $14. ($100,000 exemption at tax rate of $14.18 per $1000)

As an example, if a tax bill is $6,800, the surcharge will be $68-$14 = $54. or $13.50 a quarter. -->

### What are examples of projects that could benefit from CPA funds in Shirley?

 - Purchase of open space to protect it from development.
 - Restoration of Fredonian Park.
 - Preservation of the Center Town Hall, War Memorial building, Town cemeteries and other historic Town properties such as School House #8.
 - Benjamin Hill pool and recreation area improvements, athletic field acquisitions.

### What is the process for adopting the CPA in Shirley?

The process requires two votes in favor of adoption:
 - A majority vote at Town Meeting on November 28, 2022 (Passed)
 - A majority vote at the general Town election on May 2, 2023

### Can you tell me more about the ‘affordable housing’ aspect of the CPA?

**CPA is not bringing affordable housing to Shirley. The state is mandating that all communities include affordable and multi-family housing in their zoning, with especially strict requirements for MBTA Communities, like Shirley. CPA funds can help Shirley shape future affordable housing developments to better harmonize with our community.**

 - Affordable housing means housing for first-time home buyers and downsizing seniors, many of whose find Shirley’s current mix of housing types unaffordable, and will enable our children and senior citizens to continue to reside in Shirley 
 - Single-family homes on large lots gobble up open space at a rate that is not compatible with the rural character and outdoor recreation opportunities we value
 - Too many single family housing on large lots can also lead to higher taxes due to the additional “town-wide subsidized” costs of providing and maintaining roads, expanding emergency services, expanding school services, etc. 
 - CPA can help empower Shirley with a smart growth approach that directs affordable housing, market rate housing and business development towards areas that are already well served by existing services and infrastructure, while conserving forested and open space areas that are farther from core town services. 
 -Affordable and multi family housing clustered in the Shirley Village area with 1/2 mile of the commenter rail station, as required for MBTA Communities legislation, will help revitalize Shirley’s downtown, attracting new businesses, restaurants, etc., which will, in turn, broaden Shirley’s tax base. 

### Are donations to the campaign tax-deductible?

Federal law stipulates that campaign donations are not tax-deductible.

### Where will unused campaign funds be distributed after the campaign?

If any funds remain after all campaign expenses have been paid, the excess money will be allocated toward any eligible CPA need.

### How do I make a donation?

Make checks payable to *Campaign for Shirley CPA* and mail to:<br>
Campaign for Shirley CPA<br>
PO Box 965<br>
Shirley, MA  01464

### How can I support the CPA campaign?

1. Make a donation to the campaign 
2. Place a sign in your yard 
3. Like and share the Facebook page 
4. Reach out to (campaignforshirleycpa@gmail.com) to get hard copy flyers to hand to neighbors and friends
5. Ensure you’re registered to vote in Shirley (<b>Voter registration deadline is April 21</b>). [Confirm registration here](https://www.sec.state.ma.us/VoterRegistrationSearch/MyVoterRegStatus.aspx)
6. Commit to voting at Town Hall on May 2nd (hours: 7 AM - 8 PM) or obtain an absentee ballot by this date (By 12 PM on May 1st) [here](https://www.sec.state.ma.us/divisions/elections/languages/absentee-ballot-applications.htm).
7. Confirm your family and 10 friends are all registered and committed to voting May 2nd
8. Volunteer to serve as a Neighborhood Captain for speaking with your neighbors about the CPA.
9. Speak with 10 neighbors asking them “What do they like about living in Shirley?” and providing them with information about the CPA (i.e. [https://campaignforshirleycpa.com/](https://campaignforshirleycpa.com/))
10. Visit the Community Preservation Coalition to see how other towns have used CPA and talk with your friends and neighbors about which projects you could see happening in Shirley


<a class="button" href="#ccblock" onclick="document.getElementById('ccblock').style.display = 'block';">Signup for email updates!&nbsp; <svg width="16" height="16" class="icon  icon--email" role="img" alt="email"><title>email</title><use xlink:href="#email" fill="CurrentColor"></use></svg>
</a>


<div id="ccblock" style="display: none;">
<!-- Begin Constant Contact Active Forms -->
<script> var _ctct_m = "68e7b8c9c897d6b88692b97e7ffd0ea7"; </script>
<script id="signupScript" src="//static.ctctcdn.com/js/signup-form-widget/current/signup-form-widget.min.js" async defer></script>
<!-- End Constant Contact Active Forms -->
<!-- Begin Constant Contact Inline Form Code -->
<div class="ctct-inline-form" data-form-id="aebf5ed6-fb45-4081-9ac0-f4b6cf8a92a9"></div>
<!-- End Constant Contact Inline Form Code -->
</div>
