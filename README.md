# MassDOT ITMS Events Feed
XML Events Feed Documenation for MassDOT's ITMS.

## Schema
`xml-feed-schema.xsd` describes the shape/type of the XML feed.


Occurence:

<Recurrence>
  <StartDateTime>2018</StartDateTime>
  <EndDateTime>2019</EndDateTime>
  <Type>DAILY</Type> <!-- 'DAILY', 'WEEKLY', 'MONTHLY' -->
  <Frequency>2</Frequency> <!-- Number (Every 2 days) or 'WEEKDAY' -->
  <!-- only one of the two below -->
  <EndBy>2019</EndBy> <!-- date to end by -->
  <NumOccurences>10</NumOccurences> <!-- total number of occurrences -->
</Recurrence>
