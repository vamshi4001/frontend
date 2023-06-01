# Guide to a Frontend Engineer
A series of activities for anyone looking to make a career in front-end engineering

This guide assumes one knows Javascript. If not, JS is one of the basic things to get started as a Frontend Engineer. 

 - Find an Open API which has authentication and data along 
 - Connect to it with Express.js - that means you make pass through services 
 - Your UI will call express endpoints and express will call external API
 - that way, your UI doesn't have to know which external website is it calling. (Abstraction for security)
 - Build UI using 
       ReactJS
       Angular14
       NextJS
 - Check what is Vercel and Netlify
 - Host the app on one of those
 - Buy a sample domain (.in websites will be cheaper)
	 - Connect domain to hosted location. 
		 - Could be on Vercel/netlify
		 - Could be on AWS EC2 or ECS
		 - DNS configuration done on Godaddy/namecheap wherever you buy the domain
	 - Code should be hosted on Github
	 - Code should always have main branch and you build features in a separate branch
	 - Merge to main, only after creating a PR - never push any change to main directly
	 - Create Github actions to deploy as soon as merge to main happens
	 - Try doing the same in jenkins pipeline (check what jenkins does and what jenkins config looks like and how to setup pipeline)
	 - Find what an artifactory is - what is jfrog and what companies use it for
	 - Write unit tests for the code using jest
	 - Run them to check the test coverage
	 - Configure pre-commit git hooks to not allow a commit without 100% coverage
	 - Check how to set that threshold
	 - Write integration tests using cypress
	 - Write storybook for components created in Angular and React
	 - Write component tests for components and test via storybook
