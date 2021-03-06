Angular highlight directive
====

Angular directive to highlight text in the html container and it's children.

Usage
----
Run `npm install ngx-highlight`

Add `[highlight]="searchTerm"` directive to any block element.

Example

	...
	import { HighlightModule } from 'ngx-highlight/highlight.module';

	@NgModule({
		declarations: [
			AppComponent,
		],
		imports: [
			BrowserModule,
			FormsModule,
			HttpModule,
			HighlightModule,
		],
		providers: [],
		bootstrap: [AppComponent]
	})

	export class AppModule { }

    
And in your HTML template:

	<div [highlight]="searchTerm">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut, suscipit atque excepturi rem culpa, aperiam et. Qua
        tempora qui molestias distinctio beatae suscipit doloremque reiciendis, quisquam vel, recusandae, obcaecati dolor.
    </div>


Live demo: [https://arthurvaverko.github.io/ngx-highlight/](https://arthurvaverko.github.io/ngx-highlight/)

* Inspierd by: [https://markjs.io/](https://markjs.io/)
