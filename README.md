```typescript
namespace DuncanFaulkner {
  class About extends Me {
    get currentWorkplace() {
      return {
        company: 'Applied Satellite Technology Ltd',
        position: 'Senior Software Engineer'
      };
    }

    const dailyKnowledge = new Map([
        ['Angular','all versions'],
        ['Angular Material','all versions'],
        ['Flex-Layout','all versions'],
        ['Typescript','all versions'],
        ['Javascript','ES5, ES6, ES2015'],
        ['HTML','all versions'],
        ['SCSS','all versions'],
        ['Rxjs','4, 5 & 6'],
        ['C#','all versions'],
        ['MySql','8, 9, 10'],
        ['MSSQL','all versions'],
        ['Blogger','anglebrackets.dev'],
    ]);
    
    const futureGoal = {
        oss: 'To contribute more to open source.',
        meetup: 'Join or start a local Angular meetup.',
        training: 'Run training sessions on Angular, Angular Material.',
        book: 'Write an ebook.',
        conference: 'Speak at conferences.'
    }
  }
}
```
