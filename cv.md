# Angelina Slabko

###### Contacts
* tel: +375 29 361 21 24
* email: 27081989adel@gmail.com
* linkedin: https://www.linkedin.com/in/angelina-slabko/

###### Summary
I'm looking for a job to work in an environment which encourages me to succeed and grow professionally where I can utilize my skills and knowledge appropriately. I am open to gain experience and new knowledge.

###### Skills
* OOP
* C#
* SQL
* Git
* HTML
* CSS
* Dart

###### Code Example
*private static int[,] GetIncidenceMatrix(List<Tuple<int, int» edges, List<int> weigth, bool oriented = true)*
*{*
	*var maxEdgeNumber = edges.Select(t => Math.Max(t.Item1, t.Item2)).Max();*
	*var result = new int[maxEdgeNumber, edges.Count];*

	*for (int i = 0; i < edges.Count; i++)*
	*{*
		*var edge = edges[i];*
		*result[edge.Item1 - 1, i] = oriented ? (-1 * weigth[i]) : (1 * weigth[i]);*
		*result[edge.Item2 - 1, i] = 1 * weigth[i];*
	*}*

	*return result;*
*}*

###### Experience
**Project MyFit**
This application is developing to help people who want to lose weight. It allows you to calculate your body mass index, daily calorie intake and workout per week. 
*Skills used: * OOP, C#, MySQL, Windows Forms

###### Education
**Minsk Radio Engineering College**
*2018 - 2022*
Information technologies software
3 year
