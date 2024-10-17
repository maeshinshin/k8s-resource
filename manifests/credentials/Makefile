apply:
	for f in $$(find -iname sec*);do echo $f && kubesec decrypt $$f | kubectl apply -f - ;done
