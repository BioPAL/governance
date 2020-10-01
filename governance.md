# Main Governance Document

The official version of this document, along with a list of
individuals and institutions in the roles defined in the governance
section below, is contained in The Project Governance Repository at:

[https://github.com/biopal/governance](https://github.com/biopal/governance)


## The Project

The BIOMASS Product Algorithm Laboratory (BioPAL) Project (The Project) is an open source software project
affiliated with the European Space Agency (ESA) and BIOMASS satellite mission.
The goal of The Project is to
develop, maintain and evolve open source software and related technology for processing Level 1 (L1), Level 2 and 3 (L2/3) data of ESA's BIOMASS mission. The Project endeavors to extend the 
initially proposed algorithm suite and include the broader scientific community in the development and evolution of BioPAL algorithms. The Software developed
by The Project is released under the MIT (or similar permissive) open source license, developed openly and hosted in public GitHub repositories under the
[BioPAL GitHub organization](https://github.com/biopal). Examples of
Project Software include the tools and configurations related to the deployment of the BIOMASS L2 prototype processor. The Services run by the
Project consist of public websites and web-services that are hosted
under the [[TBD]] domains. The Services Examples of
Project Services include the BioPAL website
([TBD](TBD)).

The Project is developed by a team of distributed developers, called
Contributors. Contributors are individuals who have contributed code,
documentation, designs or other work to one or more Project repositories.
Anyone can be a Contributor. Contributors can be affiliated with any legal
entity or none. Contributors participate in the project by submitting,
reviewing and discussing GitHub Pull Requests and Issues and participating in
open and public Project discussions on GitHub, Slack chat
rooms and other channels. The foundation of Project participation is openness
and transparency.

Here is a list of the current Contributors to the main BioPAL repository:

[https://github.com/biopal/biopal/graphs/contributors](https://github.com/biopal/biopal/graphs/contributors)

There are also many other Contributors listed in the logs of other repositories of
the BioPAL project.

The Project Community consists of all Contributors and Users of the Project.
Contributors work on behalf of and are responsible to the larger Project
Community and we strive to keep the barrier between Contributors and Users as
low as possible.

The Project is formally affiliated with the European Space Agency (ESA)
([https://www.esa.int/](https://www.esa.int/)).


## Governance

Our community is structured as a virtual organization. Authority is primarily distributed to both volunteer and employed community members irrespective of employment affiliation as they show their ability through contributions to The Project. The Project also seeks to debias this system of distributing authority through active interventions that engage and encourage participation from diverse communities.

The foundations of Project governance are:

-   Openness & Transparency
-   Active Contribution
-   Institutional Neutrality

### Benevolent Dictator for Life

The ultimate decision-maker is the ESA BIOMASS Data Quality Manager: Clement Albinet, who has the final say in the case of disputes. Additionally, up to three "Benevolent Dictators for Life" (BDFL) can be appointed by ESA and in accordance to the BIOMASS Mission Manager. The BDFL model is followed by many successful open source projects. BioPAL will have at least one member of the ESA BIOMASS Mission Staff in this role: either the BIOMASS Data Quality Manager, Mission Manager, PDGS Manager or Science Manager.

As Dictator, the BDFL has the authority to make all final
decisions for The Project under the BIOMASS mission manager. As Benevolent, the BDFL, in practice chooses to
defer that authority to the consensus of the community discussion channels and
the Steering Council (see below). It is expected, that the BDFL will only rarely assert his/her final authority. We refer to BDFL’s final authority as a “special” or “overriding”
vote. When it does occur, the BDFL override typically happens in situations
where there is a deadlock in the Steering Council or if the Steering Council
asks the BDFL to make a decision on a specific matter. The BDFL is chair
of the Steering Council (see below) and may delegate his/her authority on a
particular decision or set of decisions to any other Council member or ESA employee at his/her discretion.

To become eligible to be BDFL an individual must be the BIOMASS Data Quality Manager, Mission Manager, PDGS Manager or Science Manager, and be recommended by the BIOMASS Mission Manager, or be appointed as successor by a current BDFL.
If a BDFL is unable to appoint a successor, the BIOMASS mission manager will make the final decision and appoint a BDFL successor.

### The Steering Council

The Project will have a Steering Council that consists of Project Contributors
nominated as explained below. The Steering Council should be composed of
a diverse array of backgrounds, viewpoints and talents. The overall role of the
Council is to ensure, through taking input from the Community, the long-term
well-being of The Project, scientifically, technically and as a community. 

During the everyday Project activities, Council Members participate in all
discussions, code review and other Project activities as peers with all other
Contributors and the Community. In these everyday activities, Council Members do
not have any special power or privilege through their membership on the Council.
However, it is expected that because of the quality and quantity of their
contributions and their expert knowledge of The Project Research, Software and Services
that Council Members will provide useful guidance, both technical and in terms
of Project direction, to potentially less experienced Contributors.

The Steering Council and its Members play a special role in certain situations.
In particular, the Council may, if necessary:

* Make decisions about the overall scope, vision and direction of The Project.
* Make decisions about strategic collaborations with other organizations or
  individuals.
* Make decisions about specific technical issues, features, bugs and pull
  requests. They are the primary mechanism of guiding the code review process and
  merging pull requests.
* Make decisions about the Services that are run by The Project and manage those
  Services for the benefit of The Project and Community.
* Make decisions when regular Community discussion does not produce consensus on
  an issue in a reasonable time frame.

Outcomes and decisions should be clearly communicated to the Community. This can
take two different forms: 

* New challenges for BioPAL will be detailed as a GitHub issue for the Community
  to discuss.
* Resolved technical deadlocks will result in an explanation on the relevant
  issue and/or closure of the relevant pull request.

#### Council Membership

A list of current Steering Council Members is maintained at the page [Current steering council and institutional partners](people).

To become eligible for being a Steering Council Member an individual must be a Project Contributor who has produced contributions that are substantial in
quality and quantity, and sustained over at least six months. Potential Council
Members are nominated by existing Council members and voted upon by the existing
Council, after asking if the potential Member is interested and willing to serve
in that capacity. Additionally, an individual can become eligible for being a Steering Council Member for a set period of time, when specifically appointed by the BIOMASS Mission Manager or a BDFL. The Council will be initially formed from the set of existing
Developers of the Level 2 BIOMASS prototype processor as of August, 2020.

When considering potential Members, the Council will look at candidates with a
comprehensive view of their contributions. This will include but is not limited
to code, code review, scientific research, infrastructure work, mailing and chat participation,
community help/building, education and outreach, design work, etc. We are
deliberately not setting arbitrary quantitative metrics (like “100 commits in
this repo”) to avoid encouraging behavior that plays to the metrics rather than
The Project’s overall well-being. We want to encourage a diverse array of
backgrounds, viewpoints and talents in our team, which is why we explicitly do
not define code as the sole metric on which Council Membership will be evaluated.

If a Council Member becomes inactive in The Project for a period of one year,
they will be considered for removal from the Council. Before removal, an
inactive Member will be approached by the a Council Member to see if they plan
on returning to active participation. If not they will be removed immediately
upon a Council vote. If they plan on returning to active participation soon,
they will be given a grace period of one year. If they do not return to active
participation within that time period they will be removed by vote of the
Council without further grace period. All former Council Members can be
considered for Membership again at any time in the future, like any other
Project Contributor. Retired Council Members will be listed on the Project
website, acknowledging the period during which they were active in the Council.

The Council reserves the right to eject current Members, if they are deemed to be actively harmful to the project’s well-being, and attempts at communication and conflict resolution have failed. This requires the consensus of the remaining Members and the BIOMASS Mission Manger.

#### Conflict of Interest

It is expected that Council Members will be employed at a wide range of
companies, universities and non-profit organizations. Because of this, it is
possible that Members will have conflict of interests. Such conflict of
interests include, but are not limited to:

* Financial interests, such as investments, employment, or contracting work,
  outside of The Project that may influence their work on The Project.
* Access to proprietary information of their employer that could potentially
  leak into their work with The Project.
* An issue where the person privately gains an advantage from The Project
  resources, but The Project has no gain or suffers a disadvantage.

All Members of the Council shall disclose to the rest of the Council any
conflict of interest they may have. Members with a conflict of interest in a
particular issue may participate in Council discussions on that issue, but must
recuse themselves from voting on the issue.


#### Private communications of the Council¶

To the maximum extent possible, Council discussions and activities will be public and done in collaboration and discussion with the Project Contributors and Community. The Council will be able to use private means of communication (i.e. phone calls, official ESA meetings, private e-mail). When private communications and decisions are needed, the Council will do its best to summarize those to the Community after eliding personal/private/sensitive information that should not be posted to the public internet.


## Institutional Partners and Funding

ESA is the ultimate decision-maker on the Project.
The Steering Council is appointed on behalf of ESA to act as the primary leadership for The Project in day to day activities. No outside
institution, individual or legal entity has the ability to own, control, usurp
or influence The Project other than by participating in The Project as
Contributors and Council Members. However, because institutions are the primary
funding mechanism for The Project, it is important to formally acknowledge
institutional participation in The Project. These are Institutional Partners.

An Institutional Contributor is any individual Project Contributor who
contributes to The Project as part of their official duties at an Institutional
Partner sustained over at least six months, or any Institution contributing to the Project as part of their official contract with ESA. Likewise, an Institutional Council
Member is any Project Steering Council Member who contributes to The Project as
part of their official duties at an Institutional Partner.

With these definitions, an Institutional Partner is any recognized legal entity anywhere int he world that employs at least one Institutional Contributor or
Institutional Council Member. Institutional Partners can be for-profit or
non-profit entities.

Institutions become eligible to become an Institutional Partner by employing
individuals who actively contribute to The Project as part of their official
duties. To state this another way, the only way for an Institutional Partner to
influence The Project is by actively contributing to the open development of The
Project, on equal terms with any other member of the community of Contributors
and Council Members. Merely using Project Software or Services in an
institutional context does not allow an entity to become an Institutional
Partner. Financial gifts do not enable an entity to become an Institutional
Partner. Once an institution becomes eligible for Institutional Partnership,
the Steering Council and BIOMASS Mission Manager must nominate and approve the Partnership.

If at some point an existing Institutional Partner stops having any contributing employees, then a one year grace period commences. If at the end of this one year period they continue not to have any contributing employees, then their Institutional Partnership will lapse, and resuming it will require going through the normal process for new Partnerships.

An Institutional Partner is free to pursue funding for their work on The Project through any legal means. This could involve a non-profit organization raising money from private foundations and donors or a for-profit company building proprietary products and services that leverage Project Software and Services. Funding acquired by Institutional Partners to work on The Project is called Institutional Funding. However, no funding obtained by an Institutional Partner can override the Steering Council except upon direct request by ESA or the BIOMASS Mission Manager. If a Partner has funding to do BioPAL work and the Council decides to not pursue that work as a project, the Partner is free to pursue it on their own. However in this situation, that part of the Partner’s work will not be under the BioPAL umbrella and cannot use the Project in a way that suggests a formal relationship.

Institutional Partner benefits are:
* Acknowledgement on the BioPAL websites, in talks and T-shirts.
* Ability to acknowledge their own funding sources on the BioPAL websites, in talks and T-shirts.
* Ability to influence the project through the participation of their Council Member.
* Council Members invited to BioPAL Developer Meetings.

A list of current Institutional Partners is maintained at the page [Current steering council and institutional partners](people).

# Document history¶

TBD


# Acknowledgments

Substantial portions of this document were adapted from the, Mozzilla, Jupyter/IPython and Numpy project’s governance document.


# License

To the extent possible under law, the authors have waived all copyright and related or neighboring rights to the BioPAL project governance and decision-making document, as per the CC-0 public domain dedication / license.