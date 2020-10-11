```typescript
namespace DuncanFaulkner {
  class About extends Me {
    get currentWorkplace() {
      return {
        company: 'Applied Satellite Technology Ltd',
        position: 'Senior Software Engineer'
      };
    }

    get dailyKnowledge() {
      return [
        'Angular',
        'Angular Material',
        'Flex-Layout',
        'Typescript',
        'Javascript',
        'HTML',
        'SCSS',
        'Rxjs',
        'C#',
        'MySql',
        'MSSQL'
      ];
    }

    get futureGoal() {
      return [
        'To contribute more to open source.',
        'Join or start a local Angular meetup.',
        'Run training sessions on Angular, Angular Material.',
        'Speak at conferences.'
        ];
    }
  }
}
```
