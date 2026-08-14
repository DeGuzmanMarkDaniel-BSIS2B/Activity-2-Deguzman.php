<?php
// Nickname: Denden

/*
 * Name: De Guzman, Mark Daniel 
 * Age: 19
 * Address: Paombong, Bulacan 
 * Hobbies: Gaming, Basketball 
 * Dream job: Web Developer 
 * Course: Bachelor of Science in Information System 
 * School: Bulacan Polytechnic College 
 */

$me = array(
    "name"      => "De Guzman, Mark Daniel",
    "age"       => 19,
    "address"   => "Paombong, Bulacan",
    "hobbies"   => "Gaming, Basketball",
    "dream_job" => "Web Developer",
    "course"    => "Bachelor of Science in Information System",
    "school"    => "Bulacan Polytechnic College"
);

echo "<h2>My Basic Information</h2>";
echo "<ul>";
echo "<li><strong>Name:</strong> " . $me["name"] . "</li>";
echo "<li><strong>Age:</strong> " . $me["age"] . "</li>";
echo "<li><strong>Address:</strong> " . $me["address"] . "</li>";
echo "<li><strong>Hobbies:</strong> " . $me["hobbies"] . "</li>";
echo "<li><strong>Dream Job:</strong> " . $me["dream_job"] . "</li>";
echo "<li><strong>Course:</strong> " . $me["course"] . "</li>";
echo "<li><strong>School:</strong> " . $me["school"] . "</li>";
echo "</ul>";

print "I am " . $me["name"] . ", a " . $me["course"] . " student of " . $me["school"] . ".";
?>
