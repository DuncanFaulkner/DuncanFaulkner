```typescript
namespace DuncanFaulkner {
  class About extends Me {
    get currentWorkplace() {
      return {
        company: 'Applied Satellite Technology Ltd',
        position: 'Senior Angular Engineer'
      };
    }

    const knowledge = new Map([
        ['Angular','5 years'],
        ['Angular Material','5 years'],
        ['Flex-Layout','5 years'],
        ['Typescript','5 years'],
        ['Javascript','10 years'],
        ['HTML','15 years'],
        ['SCSS','10 years'],
        ['Rxjs','5 years'],
        ['C#','10 years'],
        ['MySql','5 years'],
        ['MSSQL','15 years'],
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
