apply:
	for f in $$(find sec*);do echo $f && kubesec decrypt $$f | kubectl apply -f - ;done
