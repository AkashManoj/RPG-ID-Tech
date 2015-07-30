 int patoh()

 {
	 int pathSelect;

	pathSelect = pathSelect + 1;

	cout << "You wake up in a forest in The Vale of Enduring Songs. Looking around, you see a note. The note instructs you to journey to The Mountain of the Vale. There is a creature to be found there. A beast known only by the name Terror. He has been killing the poor residents of Vale Town, in the shadow of the Mountain. You need to end his reign of terror! Pick your path to the Terror: " << endl;
	cout << "1) Straight ahead, the forest thickens, with a trickle of sunlight reaching its way through the trees. Go this way?" << endl;
	cout << "2) To your left the forest breaks, leading to gentle rolling hills. Go this way?" << endl;
	cout << "3) The forest also breaks to your right, leading to a rocky seashore. Go towards the sea?" << endl;

	cin >> pathSelect;
	if (pathSelect == 1)
	{
		cout << "Walking through the darkest parts of the forest, you begin to hear a rustling that suggest something a bit bigger than simple leaves in the wind. All of a sudden you see a tree that wasn't there before. Its eyes open and you prepare to fight what you realize is an Ent." << endl;

	}
	else if (pathSelect == 2)
	{
		cout << "Walking through the gentle hills, you recognize that the right choice has been made. None of the peaceful residents bother you. One kind farmer even gives you a Ruby Crystal to aid you in your quest. Your health raises by 15!" << endl;
	}
	else if (pathSelect = 3)
	{
		cout << "The seashore is not as idyllic as its name suggests. The rocky landscape is unforgiving, and easily disguises the creatures lurking there. You walk straight a Giant Mudcrab, thankfully able to recover fast enough to engage." << endl;
	
	}
	return pathSelect
}
};
