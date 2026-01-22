<script>
import { Button } from '@/components/ui/button'
import { Card, CardHeader, CardTitle, CardContent, CardFooter } from '@/components/ui/card'
import { Badge } from '@/components/ui/badge'
import { ArrowLeft } from 'lucide-vue-next';

export default {
  name: 'Blog',
  components: {
    Button,
    Card,
    CardHeader,
    CardTitle,
    CardContent,
    CardFooter,
    Badge,
    ArrowLeft,
  },
  data() {
    return {
      posts: [
        {
          id: 1,
          slug: '100-days-of-entrepreneurship-day-1', // <-- Added slug
          title: '100 Days of Entrepreneurship Day 1',
          date: 'July 29, 2025',
          day: 1,
          snippet: 'I’m Hritik Gupta, 25 years old, and as of now—accomplishments? Nothing. Since I was a kid, my only passion has been creating new things and becoming an entrepreneur.',
          content: `
            <p>Hello readers,</p>
            <p>I’m Hritik Gupta, 25 years old, and as of now—accomplishments? Nothing. Since I was a kid, my only passion has been creating new things and becoming an entrepreneur. To chase that dream, I spent the last 20 years mostly daydreaming, thinking big, and ignoring almost every other aspect of life.</p>
            <p>As a result, I now find myself with a shallow understanding of many things but deep expertise in none. I’m not employable in the traditional sense—but entrepreneurship? That’s something I can still pursue. I have a ton of ideas and a little knowledge about domains ranging from product design and development to marketing and finance.</p>
            <p class="font-semibold text-primary">My plan is simple: keep launching products until one of them succeeds.</p>
            <p>The first product I started with is an ambitious one—driven by the dream of changing entertainment as we know it. , The initial idea was an interactive storytelling platform where users could participate in their favorite shows by joining a group chat with AI characters. Unlike platforms like Character.ai or CHAI, this wouldn’t be random—it would follow a proper story from beginning to end.I called it <a href="https://sitchat.ai" target="_blank" rel="noopener noreferrer" class="font-semibold text-primary hover:underline">Sitchat.ai</a> You know Sitcom but with Chat</p>
            <p>You could create any show by just giving it a name and clicking a button. You could then create episodes by typing out an idea like “Joey gets nominated for an Oscar” and actually play that episode as a character. I thought it was a wild idea—something that would go viral instantly, make me famous, and turn me into a millionaire.</p>
            <p>So, I spent March and April building the prototype, which was ready by May. I launched it and shared it wherever I thought it was relevant. But by the end of May, all I had managed was 135 users—most of them one-time visitors.</p>
            <p>I assumed it was because it was a web app, so I started building a mobile version. That too failed.</p>
            <p>Then I went through the chat data and noticed that while users weren’t interacting much, they were completing the chats. This led me to an important realization: people were interested in reading the stories, not interacting with them.</p>
            <p>So I decided to pivot—to turn the app into a fan fiction storytelling platform. Users could create episodes, and those episodes would be transformed into podcasts, basic videos, and comics. The interactive version would still exist, but the focus would shift.</p>
            <p>This sparked new hope.</p>
            <p>Then in June, I went to Chennai to collect my degree. But there, I started experiencing unbearable pain in my lower back. When I got back and visited the doctor, it turned out to be Pilonidal Sinus, and I needed immediate surgery.</p>
            <p>After the surgery came two months of bedrest. The first month, I couldn’t do anything. The second month—July—I could sit and work, but instead, I spent my days doomscrolling and watching Netflix. I didn’t understand why I wasn’t working. Why was I wasting so much time?</p>
            <p>It wasn’t until I read <em class="italic text-primary/90">Tiny Experiments</em> by Anne-Laure Le Cunff that it clicked. I had been focusing too much on outcomes, and my first failure had scared me. The book teaches that we should shift our focus from results to the work itself. When we do that, the fear and anxiety subside, and procrastination goes away. The easiest way to implement this? Create a commitment like this one: 100 Days of Entrepreneurship.</p>
            <p class="font-semibold text-primary">Now, I don’t care about the outcome—I'm just showing up and doing the work, driven by curiosity, not results. Every day, for the next 100 days, I’ll write a blog.</p>
            <p>Today is Day 1.</p>
            <p>I’m kicking things off by reviewing all the work I did before I fell sick, making a future roadmap, and going through the chat data from those 135 users (not all of them today, but gradually). My goal is to revamp the app into a fan-based storytelling platform. Here’s what I plan to add:</p>
            <ul class="list-disc list-inside space-y-2 pl-4">
              <li>Voice cloning and an audio version of the stories</li>
              <li>A comic version</li>
              <li>A video version using Veo 3 and Heygen AI</li>
              <li>Launch the app on the App Store and Play Store using Capacitor.js</li>
              <li>Improve the UI to make it more intuitive</li>
              <li>Add a basic tutorial for first-time users</li>
            </ul>
            <p class="font-bold text-center pt-4">Let the journey begin.</p>
          `
        },
        {
          id: 2,
          slug: 'TypeMyVibe-Take-2-day-1', // <-- Added slug
          title: 'TypeMyVibe Take 2 Day 1',
          date: 'January 20, 2025',
          day: 1,
          snippet:'I started a blog series titled 100days of entrepreneurship where I planned to record my journey as an indie hacker. The 100days should have finished by November but the last blog I wrote was at the end of November and it was just the 55th blog. I was only writing when I was productive and making some progress. The blogs were mostly a sob story of how I struggle with productivity but the writings did help me articulate better, prompt better,  know where I stand and gave me direction of where I should go. So after wasting another 2 months I am starting my journey again. Hopefully I am consistent this time and succeed. ',
          content: `
             <p>Hello everyone,</p>

    <p>
      I started a blog series titled <strong>100 days of entrepreneurship</strong> where I planned to record my journey as an indie hacker.
      The 100 days should have finished by November, but the last blog I wrote was at the end of November and it was just the 55th blog.
      I was only writing when I was productive and making some progress.
    </p>

    <p>
      The blogs were mostly a sob story of how I struggle with productivity, but the writing did help me articulate better, prompt better,
      understand where I stand, and gave me direction on where I should go.
      After wasting another two months, I am starting my journey again.
      Hopefully I am consistent this time and succeed.
    </p>

    <p>
      When I started the blog, I was working on <strong>Sitchat</strong>, which was an interactive storytelling platform using group chats with AI.
      I believed it was a great idea and could be made into something big.
      I still do, but I realized it was out of my current abilities and would require a team and funding.
    </p>

    <p>
      After struggling for 10–15 days writing about Sitchat, I started working on <strong>TypeMyVibe</strong>,
      which uses AI to analyze people’s social media profiles or chats to generate a detailed personality report.
      This was something I had been interested in for a long time.
    </p>

    <p>
      It took me about one and a half months to build it, with a lot of inconsistency.
      Then I started posting about it on Reddit and got some initial traction.
      I also tried Google Ads and Reddit Ads.
      I spent around <strong>$500</strong> and earned <strong>$110</strong>.
    </p>

    <p>
      Then, for some goddamn reason, I stopped.
      I realized I had a lot of hard work ahead of me.
      I needed to study psychology and marketing to make the product actually useful,
      because until then it was mostly a toy product.
      I also needed to learn how to reach people more effectively and economically to be profitable.
    </p>

    <p>
      This was overwhelming, and I procrastinated badly.
      I bought books on psychology and marketing, read occasionally,
      but gained no concrete insights that helped me improve the product.
    </p>

    <p>
      Now I am back to work.
      I am a little overwhelmed about where to start after not working at all for two months.
      After spending the whole day with the code and platform, here are the things I believe I should be working on
      to achieve my goal of earning <strong>$10k MRR</strong> by the end of this year.
    </p>

    <ol>
      <li>Make the report more personalized by using insights from chats or social media profiles, making each report truly unique.</li>
      <li>Update the prompts for analysis to improve accuracy.</li>
      <li>Fix and continue the blog.</li>
      <li>Update and improve the personality database.</li>
      <li>Restrict the freemium version to improve unit economics.</li>
      <li>Improve the UI of the report.</li>
      <li>Add a Discord option.</li>
      <li>Set up an email marketing system to convince people to buy.</li>
      <li>Provide options for open-source models and closed-source models for privacy and better results.</li>
      <li>
        Start marketing now. I am still confused whether to focus on short-form content or Reddit/X.
      </li>
      <li>Set up proper analytics using PostHog.</li>
    </ol>

    <p>
      Just doing and achieving the above things should help me get closer to my goal.
      I will update the blog every day with the progress I make.
      Every day, I will spend the first half coding and making required changes,
      and the second half learning and marketing.
    </p>

    <p>
      Initially, I will try to do all marketing organically and focus on only one channel:
      either short-form content or Reddit/X.
    </p>
          `
        },
        {
          id: 3,
          slug: 'TypeMyVibe-Take-2-Day-2', // <-- Added slug
          title: 'TypeMyVibe Take 2 Day 2',
          date: 'January 22, 2025',
          day: 2,
          snippet:'It’s the second day and I forgot to write the blog. So I am writing it on the 3rd day but will write one at the end of the day too. ',
          content: `
          <p>
    Hello everyone,
  </p>

  <p>
    It’s the second day and I forgot to write the blog. So I am writing it on the 3rd day but will write one at the end of the day too.
  </p>

  <p>
    On the second day in the morning, I was using and checking a product called Aftermark AI. Its founder had reached out to me on X. The product is insanely good and I think it will be really helpful for me at the beginning.
  </p>

  <p>
    I can use it to find engagement on Reddit and comment using it. I can create a variety of content using their AI like slideshow posts, wall of text, green screen memes, hook plus product demos, and Reddit posts. I can also schedule posts using it. So it’s going to be insanely helpful in marketing.
  </p>

  <p>
    The founder is asking me for $90 per month and I think I will go for it. Investing now will make sure I start marketing and do not procrastinate anymore.
  </p>

  <p>
    After that, I started working on the email marketing setup. When a user signs up but doesn’t make a report, they will get nudge emails to make a report. If they make a report but don’t purchase, they will get a conversion email.
  </p>

  <p>
    The emails will be sent 1 day after, 3 days after, and 7 days after. I hope this increases the report creation and conversion rates.
  </p>

  <p>
    I used AI to generate the emails and tested them on the live server. When I started the test, it sent 200 emails and exhausted my free daily limit. I will continue testing it today.
  </p>

  <p>
    This was a bit sad, but I got a 10% CTR from the 200 emails, which was insanely good.
  </p>

  <p>
    Next, I procrastinated by calculating what I need to do to reach my $10k MRR goal. I got the data for the last 2 months:
  </p>

  <ul>
    <li>600k impressions</li>
    <li>6k visits</li>
    <li>655 signups</li>
    <li>300 reports created</li>
    <li>15 sales</li>
  </ul>

  <p>
    So my CTR is 1%, visit to signup rate is 11%, signup to report creation is 50%, and report creation to purchase is 5%.
  </p>

  <p>
    Overall, views to purchase is 0.0025%, which means 1 sale per 40k views.
  </p>

  <p>
    To reach my goal of $10k MRR, I need 400 sales per month at $25 each, which is around 13–14 sales daily.
  </p>

  <p>
    At my current conversion rates, I would need:
  </p>

  <ul>
    <li>530k views daily</li>
    <li>5.3k visitors</li>
    <li>582 signups</li>
    <li>267 reports created</li>
    <li>14 sales</li>
  </ul>

  <p>
    My cost per free report is $1 and fixed costs are around $300. At a 5% report-to-purchase rate, I would need 60 days per month to break even. At $10k MRR, the profit would be around $1,700.
  </p>

  <p>
    These numbers do not look favorable. At my current conversion rates, it would be very hard to scale.
  </p>

  <p>
    I need to improve my CTR with better targeting, improve my signup rate with better messaging, report creation seems fine, and I definitely need to improve sales.
  </p>

  <p>
    If I can do that, the required views could drop to around 100k per day, which is much more achievable than 500k daily.
  </p>

  <p>
    My unit economics are also not good. I need to modify the freemium model. I plan to limit users to 2 free reports and generate the full report only after payment. This should significantly reduce costs.
  </p>

  <p>
    Let’s see how it goes. It’s going to be really difficult, but I will achieve it no matter what.
  </p>

  <p>
    After procrastinating with numbers, I went back to the core task: creating new reports. I went through the analysis and reports and wrote down my thoughts on what can be improved. I gained a lot of insights and will implement them soon.
  </p>

  <h2>Goal for Tomorrow (Today)</h2>

  <ul>
    <li>Get the email marketing system fully working and live</li>
    <li>Make some code refactors</li>
    <li>Implement insights gained from report analysis</li>
  </ul>
          `
        },
        {
          id: 4,
          slug: 'TypeMyVibe-Take-2-Day-3', // <-- Added slug
          title: 'TypeMyVibe Take 2 Day 3',
          date: 'January 23, 2025',
          day: 3,
          snippet:"Today I tested the email marketing feature and it worked as it was supposeto while testing. Sending email every minute for both nudge for report andconversion to paid. Then i pushed it live where it should send email on day1, 3 and 7 but it was sending it out every hour. Fixed that and hopefully itworks properly now.",
          content: `
          <p>Hello everyone,</p>

    <p>
      Today I tested the email marketing feature and it worked as it was suppose
      to while testing. Sending email every minute for both nudge for report and
      conversion to paid. Then i pushed it live where it should send email on day
      1, 3 and 7 but it was sending it out every hour. Fixed that and hopefully it
      works properly now.
    </p>

    <p>
      Then I refactored the code of api as it was a 3k line of monolith file.
      Codex fucking one shot it without any bugs. Crazy!
    </p>

    <p>
      Then it was time to do the most important work. Changing the algorithm. I
      procrastinated hard before starting this and when i did start I took the
      easy way out. Told claude the changes that I need and how it should work.
      It made those changes the results were better but not by much. Then asked
      it for some more changes and now the analysis much worse than it was before.
      I need to work hard on this and get this to work like how I want it to. The
      whole success of the product depends on this.
    </p>

    <p>
      While procrastinating I read an interesting article. Where the writer said
      that he was not doing what he should be doing because doing that means he
      might fail and become who had a lot of potential from failure. This
      resonated with me a lot. I am someone with a lot of potential according to
      me. I keep delaying to keep this delusion alive. Cause as soon as I start
      the illusion might shatter and I am protecting that. I need to stop
      delaying and embrace failure cause thats the only way to grow.
    </p>

    <p>
      Tomorrow I will get the algorithm to work exactly like how I want it to in
      the first half and in the second half I will iterate on the prompts of each
      section to make it valuable. This week is the last week I will work on the
      algorithm till further feedbacks from the users come.
    </p>

    <p>
      February 1st the day I will start doing marketing everyday.
    </p>

    <p>
      Thats the plan for now. Let’s see how everything goes.
    </p>
            `
        }
        // Future blog posts will be added here with their own unique slug
      ] 
    };
  },
  computed: {
    // This computed property finds the post that matches the slug in the URL
    currentPost() {
      const slug = this.$route.params.slug;
      if (!slug) return null;
      return this.posts.find(post => post.slug === slug);
    },
    sortedPosts() {
      return this.posts.sort((a, b) => b.id - a.id);
    }
  },
  // We no longer need the 'methods' block for selectPost/goBack
}
</script>

<template>
  <div class="min-h-screen relative overflow-hidden bg-background py-20 md:py-24">
    <div class="container mx-auto px-4">
      <main class="max-w-6xl mx-auto">
        <div v-if="currentPost">
          <Button as-child variant="outline" class="mb-8 gap-2">
            <RouterLink to="/blog">
              <ArrowLeft class="h-4 w-4" />
              Back to Blog List
            </RouterLink>
          </Button>
          <Card class="w-full shadow-lg">
            <CardHeader class="p-8 md:p-12">
              <CardTitle
                class="text-4xl md:text-5xl font-bold text-center mb-4 bg-gradient-to-r from-primary to-secondary bg-clip-text text-transparent"
                id="text"
              >
                {{ currentPost.title }}
              </CardTitle>
              <div
                class="flex flex-wrap items-center justify-center gap-x-4 gap-y-2 text-muted-foreground mt-4"
              >
                <span>By Hritik Gupta</span>
                <span class="hidden md:inline">|</span>
                <span>Published on {{ currentPost.date }}</span>
                <Badge variant="secondary" class="ml-2">Day {{ currentPost.day }}</Badge>
              </div>
            </CardHeader>
            <CardContent
              class="p-8 md:p-12 text-lg text-foreground/90 leading-relaxed space-y-6"
              v-html="currentPost.content"
              id="text"
            >
            </CardContent>
          </Card>
        </div>

        <!-- Blog list -->
        <div v-else>
          <h1
            class="text-5xl font-bold text-center mb-12 bg-gradient-to-r from-primary to-secondary bg-clip-text text-transparent"
            id="text"
          >
            My Blog
          </h1>

          <!-- Grid layout -->
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <Card
              v-for="post in sortedPosts"
              :key="post.id"
              class="hover:shadow-xl transition-shadow duration-300"
            >
              <RouterLink :to="'/blog/' + post.slug" class="block">
                <CardHeader>
                  <CardTitle
                    class="text-2xl font-bold group-hover:text-primary"
                    id="text"
                  >
                    {{ post.title }}
                  </CardTitle>
                  <div
                    class="flex items-center gap-4 text-sm text-muted-foreground pt-2"
                  >
                    <span>{{ post.date }}</span>
                    <Badge variant="outline">Day {{ post.day }}</Badge>
                  </div>
                </CardHeader>
                <CardContent>
                  <p class="text-muted-foreground" id="text">
                    {{ post.snippet }}
                  </p>
                </CardContent>
                <CardFooter>
                  <p class="text-primary font-semibold">Read More &rarr;</p>
                </CardFooter>
              </RouterLink>
            </Card>
          </div>
        </div>
      </main>
    </div>

    <!-- background decoration -->
    <div class="absolute inset-0 -z-10 overflow-hidden pointer-events-none">
      <div
        class="absolute right-20 top-1/3 h-72 w-72 rounded-full bg-primary/10 blur-3xl"
      ></div>
      <div
        class="absolute left-32 bottom-1/4 h-64 w-64 rounded-full bg-secondary/10 blur-3xl"
      ></div>
    </div>
  </div>
</template>
