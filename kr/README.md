# 프로그래머 되는 법 : 커뮤니티 버전 How to be a Programmer: Community Version
[//]: # (Version:1.1.0)
Robert L. Read 와 커뮤니티

Copyright 2002, 2003, 2016 Robert L. Read

[크리에이티브 커먼즈 저작자표시-동일조건변경허락 4.0 국제 라이선스 Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

[온라인(gitbook)에서 읽거나 오프라인 다운로드(PDF, ePub, Mobi)가 가능합니다.](https://www.gitbook.com/book/braydie/how-to-be-a-programmer/details)

[원문 영문판은 양장본으로 구입하실 수 있습니다(가격은 책 제작비+배송비).](http://www.blurb.com/b/6999069-how-to-be-a-programmer) - 1판, 2016/01/04

## 서론
좋은 프로그래머가 되는 것은 어렵고 숭고합니다. 소프트웨어 프로젝트의 공동 비전을 실현하는 데 있어 가장 어려운 부분은 동료와 고객을 상대하는 것입니다. 컴퓨터 프로그램을 작성하는 것은 중요하며 훌륭한 지능과 기술을 필요로 합니다. 하지만 좋은 프로그래머는 고객, 같이 일하는 무수한 동료를 동시에 만족시키는 소프트웨어를 만들어야만 한다는 것에 비하면 다른 건 애들 장난입니다. 이 글은 제가 스물 한살이였을때 누군가 알려주면 좋았을 것들을 가능한 간결하게 요약한 것입니다.

이 글은 매우 주관적이므로 개인적인 의견이 다소 많고 독단적일 것입니다. 저는 프로그래머가 일할 때 직면하는 문제에 국한시키려고 합니다. 대부분의 문제들과 해결책은 보편적이어서 아마 설교처럼 보일 것입니다. 그럼에도 불구하고 이 글이 도움이 되길 바랍니다.

컴퓨터 프로그래밍은 코스로 가르칩니다. 훌륭한 책들은 다음과 같습니다. 실용주의 프로그래머 Pragmatic Programmer [Prag99], 코드 컴플리트 Code Complete [CodeC93], 프로젝트 쾌속 개발 전략 Rapid Development [RDev96] 및 익스트림 프로그래밍 Extreme Programming Explained[XP99]은 모두 컴퓨터 프로그래밍과 훌륭한 프로그래머가 되기 위한 더 큰 이슈를 가르쳐줍니다. Paul Graham [PGSite]와 Eric Raymond [Hacker]의 에세이는 이 글 전에 읽거나 함께 읽어야 합니다. 그 저작들과는 달리 이 에세이는 사회적 문제를 강조하고 제가 보기에 필요한 기술들을 종합적으로 요약합니다.
ㄴ
이 글에서 상관 boss 이라는 용어는 당신이 할 프로젝트를 주는 사람을 가리킵니다. 비즈니스 business , 회사 company, (특정 관심사의)집단 tribe 은 동의어로 쓰였습니다. 단, 비즈니스는 돈벌이, 회사는 직장, 집단은 특정 대상에 대해 충성하는 사람들을 의미합니다.

집단 tribe 에 오신 것을 환영합니다.

## 목차

**[중국어](zh/README.md) 와 [일본어](jp/README.md)로도 번역되어 있습니다.**

1. [초보자 Beginner](ko/1-Beginner)
    - 개인 스킬
        - [디버깅하는 법 배우기](ko/1-Beginner/Personal-Skills/01-Learn-To-Debug.md)
        - [How to Debug by Splitting the Problem Space](en/1-Beginner/Personal-Skills/02-How-to-Debug-by-Splitting-the-Problem-Space.md)
        - [How to Remove an Error](en/1-Beginner/Personal-Skills/03-How-to-Remove-an-Error.md)
        - [How to Debug Using a Log](en/1-Beginner/Personal-Skills/04-How-to-Debug-Using-a-Log.md)
        - [성능 문제를 이해하는 법](ko/1-Beginner/Personal-Skills/05-How-to-Understand-Performance-Problems.md)
        - [성능 문제를 해결하는 법](ko/1-Beginner/Personal-Skills/06-How-to-Fix-Performance-Problems.md)
        - [How to Optimize Loops](en/1-Beginner/Personal-Skills/07-How-to-Optimize-Loops.md)
        - [How to Deal with I/O Expense](en/1-Beginner/Personal-Skills/08-How-to-Deal-with-IO-Expense.md)
        - [How to Manage Memory](en/1-Beginner/Personal-Skills/09-How-to-Manage-Memory.md)
        - [How to Deal with Intermittent Bugs](en/1-Beginner/Personal-Skills/10-How-to-Deal-with-Intermittent-Bugs.md)
        - [How to Learn Design Skills](en/1-Beginner/Personal-Skills/11-How-to-Learn-Design-Skills.md)
        - [How to Conduct Experiments](en/1-Beginner/Personal-Skills/12-How-to-Conduct-Experiments.md)
    - 협업 스킬
        - [Why Estimation is Important](en/1-Beginner/Team-Skills/01-Why-Estimation-is-Important.md)
        - [How to Estimate Programming Time](en/1-Beginner/Team-Skills/02-How-to-Estimate-Programming-Time.md)
        - [How to Find Out Information](en/1-Beginner/Team-Skills/03-How-to-Find-Out-Information.md)
        - [How to Utilize People as Information Sources](en/1-Beginner/Team-Skills/04-How-to-Utilize-People-as-Information-Sources.md)
        - [How to Document Wisely](en/1-Beginner/Team-Skills/05-How-to-Document-Wisely.md)
        - [How to Work with Poor Code](en/1-Beginner/Team-Skills/06-How-to-Work-with-Poor-Code.md)
        - [How to Use Source Code Control](en/1-Beginner/Team-Skills/07-How-to-Use-Source-Code-Control.md)
        - [How to Unit Test](en/1-Beginner/Team-Skills/08-How-to-Unit-Test.md)
        - [Take Breaks when Stumped](en/1-Beginner/Team-Skills/09-Take-Breaks-when-Stumped.md)
        - [How to Recognize When to Go Home](en/1-Beginner/Team-Skills/10-How-to-Recognize-When-to-Go-Home.md)
        - [How to Deal with Difficult People](en/1-Beginner/Team-Skills/11-How-to-Deal-with-Difficult-People.md)
2. [중급 Intermediate](en/2-Intermediate)
    - 개인 스킬
        - [How to Stay Motivated](en/2-Intermediate/Personal-Skills/01-How-to-Stay-Motivated.md)
        - [How to be Widely Trusted](en/2-Intermediate/Personal-Skills/02-How-to-be-Widely-Trusted.md)
        - [How to Tradeoff Time vs. Space](en/2-Intermediate/Personal-Skills/03-How-to-Tradeoff-Time-vs-Space.md)
        - [How to Stress Test](en/2-Intermediate/Personal-Skills/04-How-to-Stress-Test.md)
        - [How to Balance Brevity and Abstraction](en/2-Intermediate/Personal-Skills/05-How-to-Balance-Brevity-and-Abstraction.md)
        - [How to Learn New Skills](en/2-Intermediate/Personal-Skills/06-How-to-Learn-New-Skills.md)
        - [Learn to Type](en/2-Intermediate/Personal-Skills/07-Learn-to-Type.md)
        - [How to Do Integration Testing](en/2-Intermediate/Personal-Skills/08-How-to-Do-Integration-Testing.md)
        - [Communication Languages](en/2-Intermediate/Personal-Skills/09-Communication-Languages.md)
        - [Heavy Tools](en/2-Intermediate/Personal-Skills/10-Heavy-Tools.md)
        - [How to analyze data](en/2-Intermediate/Personal-Skills/11-How-to-analyze-data.md)
    - 협업 스킬
        - [How to Manage Development Time](en/2-Intermediate/Team-Skills/01-How-to-Manage-Development-Time.md)
        - [How to Manage Third-Party Software Risks](en/2-Intermediate/Team-Skills/02-How-to-Manage-Third-Party-Software-Risks.md)
        - [How to Manage Consultants](en/2-Intermediate/Team-Skills/03-How-to-Manage-Consultants.md)
        - [How to Communicate the Right Amount](en/2-Intermediate/Team-Skills/04-How-to-Communicate-the-Right-Amount.md)
        - [How to Disagree Honestly and Get Away with It](en/2-Intermediate/Team-Skills/05-How-to-Disagree-Honestly-and-Get-Away-with-It.md)
    - 판단내리기 Judgment
        - [How to Tradeoff Quality Against Development Time](en/2-Intermediate/Judgment/01-How-to-Tradeoff-Quality-Against-Development-Time.md)
        - [How to Manage Software System Dependence](en/2-Intermediate/Judgment/02-How-to-Manage-Software-System-Dependence.md)
        - [How to Decide if Software is Too Immature](en/2-Intermediate/Judgment/03-How-to-Decide-if-Software-is-Too-Immature.md)
        - [How to Make a Buy vs. Build Decision](en/2-Intermediate/Judgment/04-How-to-Make-a-Buy-vs-Build-Decision.md)
        - [How to Grow Professionally](en/2-Intermediate/Judgment/05-How-to-Grow-Professionally.md)
        - [How to Evaluate Interviewees](en/2-Intermediate/Judgment/06-How-to-Evaluate-Interviewees.md)
        - [How to Know When to Apply Fancy Computer Science](en/2-Intermediate/Judgment/07-How-to-Know-When-to-Apply-Fancy-Computer-Science.md)
        - [How to Talk to Non-Engineers](en/2-Intermediate/Judgment/08-How-to-Talk-to-Non-Engineers.md)
3. [숙련 Advanced](en/3-Advanced)
    - 기술적 판단 Technological Judgment
        - [How to Tell the Hard From the Impossible](en/3-Advanced/Technical-Judgment/01-How-to-Tell-the-Hard-From-the-Impossible.md)
        - [How to Utilize Embedded Languages](en/3-Advanced/Technical-Judgment/02-How-to-Utilize-Embedded-Languages.md)
        - [Choosing Languages](en/3-Advanced/Technical-Judgment/03-Choosing-Languages.md)
    - 슬기로운 타협 Compromising Wisely
        - [How to Fight Schedule Pressure](en/3-Advanced/Compromising-Wisely/01-How-to-Fight-Schedule-Pressure.md)
        - [How to Understand the User](en/3-Advanced/Compromising-Wisely/02-How-to-Understand-the-User.md)
        - [How to Get a Promotion](en/3-Advanced/Compromising-Wisely/03-How-to-Get-a-Promotion.md)
    - 팀을 위한 봉사 Serving Your Team
        - [How to Develop Talent](en/3-Advanced/Serving-Your-Team/01-How-to-Develop-Talent.md)
        - [How to Choose What to Work On](en/3-Advanced/Serving-Your-Team/02-How-to-Choose-What-to-Work-On.md)
        - [How to Get the Most From Your Team-mates](en/3-Advanced/Serving-Your-Team/03-How-to-Get-the-Most-From-Your-Teammates.md)
        - [How to Divide Problems Up](en/3-Advanced/Serving-Your-Team/04-How-to-Divide-Problems-Up.md)
        - [How to Handle Boring Tasks](en/3-Advanced/Serving-Your-Team/05-How-to-Handle-Boring-Tasks.md)
        - [How to Gather Support for a Project](en/3-Advanced/Serving-Your-Team/06-How-to-Gather-Support-for-a-Project.md)
        - [How to Grow a System](en/3-Advanced/Serving-Your-Team/07-How-to-Grow-a-System.md)
        - [How to Communicate Well](en/3-Advanced/Serving-Your-Team/08-How-to-Communicate-Well.md)
        - [How to Tell People Things They Don't Want to Hear](en/3-Advanced/Serving-Your-Team/09-How-to-Tell-People-Things-They-Dont-Want-to-Hear.md)
        - [How to Deal with Managerial Myths](en/3-Advanced/Serving-Your-Team/10-How-to-Deal-with-Managerial-Myths.md)
        - [How to Deal with Organizational Chaos](en/3-Advanced/Serving-Your-Team/11-How-to-Deal-with-Organizational-Chaos.md)
4. [용어 사전](en/GLOSSARY.md)
5. [부록 A - Bibliography/Websiteography](en/5-Bibliography.md)
6. [부록 B - History (As of January 2016)](en/6-History.md)
6. [부록 C - Contributions (As of January 2016)](en/7-Contributions.md)


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">'프로그래머 되는 법 : 커뮤니티 버전</span> <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">지은이- Robert L. Read 와 커뮤니티'는 </span> <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">크리에이티브 커먼즈 저작자표시-동일조건변경허락 4.0 국제 라이선스</a> 하에 있습니다.
