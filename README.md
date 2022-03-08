# Media-buying-with-docplex

Solving media-buying constraints with linear programming using docplex in the IBM Watson Studio
===

Media planners, as their title suggests, plan advertising placements for their campaigns across a variety of different platforms. This planning involves a certain amount of media-buying, wherein third party media must be purchased according to the demands of the campaign. This is an incredibly messy process, with media planners often unable to sort through and adequately compare different publishers' offerings for sponsored content, such as articles or videos. 

In this typical example, a media planner is given constraints by their organization. They need to hit two audiences served by two different publications.

Assume Publication 1 {pub1} is a B2B-focused technology news platform that serves the Southeast Asia market, and Publication 2 {pub2} is a B2B-focused technology news platform that serves the ANZ market. 

Publication 1 receives higher viewership at lower cost, but serves a less valuable customer for readers of its branded content (measured in the click-through rates provided). Publication 2 receives lower viewership at higher cost, but serves a more valuable customer as defined by click-through numbers.

The task of the media planner is to maximize their given budget ($30,000) and allocate it efficiently across the two publications.

This notebook shows how to use the docplex solver for the purpose of maximizing budget given a set of constraints for media planning
