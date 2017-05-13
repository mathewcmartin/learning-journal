#LJ-code301-day5#

5/12/17

Today we had a "Form Building Workshop" and Jason Greer of GeneralUI and Missoula MT was the presenter during power hour.

Additionally we had a scheduled paired portfolio assignment which was a paired programming review. My partner and I have deferred until after meeting with class members on Sunday for Code Wars at campus.

Sam discussed the A11y project, A community driven effort to make web accessibility easier.   A11yproject.com  I have always had a fear, almost a premonition that I will lose my sight during my lifetime. This prompted me to ask Sam about braille devices to which he responded with the above about A11y project. Really fascinating stuff! I want to attend their meetup next Thurs.

We had extensive code review during the day and cover a ton of material with respect to forms, jQuery, templating, CSS and HTML best use interacting with JS.

Some highlights covered included:
        []Template literals are enclosed in backticks.
        []We use square brackets to access an objects value.  
            Example:   if ($(`#author-filter option[value=”${val}”]`).length === 0) {
                                  $(‘author-filter’).append(optionTag);
                              }
        []Triple equals is called a ligature.
        []Ternary operator:
            Example:
                              publishedOn: $(‘#article-published:checked’).length ? new Date() : null
                              ~It is basically an if/else statement with the statement after the "?" before the ":" is the "if" part and that following the ":" is the "else."

In closing, it was the end to an intensive week of review and new material almost entirely addressed to viewing websites and how they appear in HTML and to the end user of the data. We have completely rewritten the processes we learned in 201 dealing primarily in vanilla javascript with tools designed to make the process easier. jQuery in particular makes selecting CSS elements far easier and manipulating them with multiple methods covering just about any sort of data manipulation one could currently imagine though the limitations are seemingly endless.

Code Fellows continues to imbue the importance of human interactions and psychology in our daily lives and the potential impact that has on our professional futures. I'm enjoying the interactions with my cohort and campus folks all vying under intense pressures, yet, ultimately learning and moving forward with collectively making this a more livable and lovable place. I have been challenged personally on several occasions reminding me of the importance of respect for others and how actions can often be misinterpreted or misunderstood absent a clear intent. I have a tendency to gently 'rib' others and now recognize that not all folks respond in manner in which I'd hope.

The most significant interpersonal growth I experienced was ironically in reaching out to others in an effort to salvage some good from a negative situation I'd created and leveraging that into remedying the problem. I was able to turn what was an unfortunate miscommunication into what I hope to be a flourishing friendship. Empathy has kicked the door of narcissism down and 'bum rushed' my personal stage. I kind of feel like that vulnerable kid I'd have nightmares about, looking around class and realizing I'd mistakenly come to school in my birthday suit. Code Fellows is giving me the courage to speak up while at the same time cover up just enough to maintain some dignity and respect from others in the end. How I'm getting back home with some remaining dignity is partly dependent on others and that's where that previous empathy pays great dividends. I'm still a bit afraid that the instructor will call on me to stand up and answer some jQuery. Perhaps this is why free t-shirts are available on campus... simply to waylay the fears of those of us who come stumbling out of the dark into Code Fellows bright and hopeful light.
