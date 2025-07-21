Hello government members!
This is the official site for showcasing all CCW permits within LARP.

Here is how you can add someone's CCW, you first need three things:
1. Discord Username
2. Roblox Username
3. CCW Type (Personal Carry, Employment-Based, High-Risk CCW)

After you got all these information you copy this section below:

<!--Copy and paste this section-->
    <div id="permitGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="permit-card bg-white rounded-lg shadow-md p-6 border-l-4 border-blue-500">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-semibold text-gray-800">DISCORD USERNAME HERE</h3>
                <span class="bg-green-100 text-green-800 text-xs px-2 py-1 rounded-full">Active</span>
            </div>
            <div class="space-y-2">
                <div class="flex justify-between">
                    <span class="text-gray-600">Discord:</span>
                    <span class="font-medium">@DISCORD USERNAME HERE</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-gray-600">Roblox:</span>
                    <span class="font-medium roblox-username">ROBLOX USERNAME HERE</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-gray-600">CCW Type:</span>
                    <span class="font-medium">CCW TYPE HERE</span>
                </div>
            </div>
        </div>
<!--Copy and paste this section-->

Looking closely at the code, there are 4 things you need to edit. First is just pasting the discord username in "DISCORD USERNAME HERE".
Keep in mind there are two of them one is without the @ which is the first one and the other one is with the @.

For instance, if I were to do it for myself I would do:

<!----------------------------------------------------------------------->
    <div id="permitGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="permit-card bg-white rounded-lg shadow-md p-6 border-l-4 border-blue-500">
            <div class="flex items-center justify-between mb-4">
                <h3 class="text-lg font-semibold text-gray-800">Alexjohn_</h3>
                <span class="bg-green-100 text-green-800 text-xs px-2 py-1 rounded-full">Active</span>
            </div>
            <div class="space-y-2">
                <div class="flex justify-between">
                    <span class="text-gray-600">Discord:</span>
                    <span class="font-medium">@alexjohn_</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-gray-600">Roblox:</span>
                    <span class="font-medium roblox-username">nvarhogr123</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-gray-600">CCW Type:</span>
                    <span class="font-medium">High-risk Special</span>
                </div>
            </div>
        </div>
  <!----------------------------------------------------------------------->

  The rest is super easy, just go to the index.html page click on the pen icon to enter editing mode and paste this section. BUT you need to know where to paste it, you can't just past it where you like..

If you look closely, I added a note at line 50. You need to past this section of code right below my note so right below line 50. 

Additionally if you would like to remove someone's CCW, you can do two things:
1. Remove the entire section (Not reccomended)
2. Edit two basic things in the code.

Go to the fifth line of the code and find the word "active", replace it with "Suspended". Additionally go a few words back and you can see "bg-green-100 text-green-800", replace both 'green's with 'red'.


YOUR JOB IS TO ONLY ADD/REMOVE/EDIT CCW PERMITS, MESSING WITH ANY OTHER PART OF THE CODE WILL RESULT IN HEAVY CONSEQUENCES. I ALREADY HAVE BACKUP OF THIS CODE SO DON'T TRY TO MAKE THE WEBSITE GO DOWN OR SOMETHING, ADDITIONALLY IF YOU MAKE ANY MISTAKES DON'T COMMIT CHANGES AND GO BACK THEN START ALL OVER AGAIN. IF NEEDED ONLY PING @ALEXJOHN_ AS HE IS THE DEVELOPER. 
